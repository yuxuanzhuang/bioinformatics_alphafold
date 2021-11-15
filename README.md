# Introduction to Bioinformatics Computer Lab

## Learning Outcomes
- get familiar with Linux commands
- know some very basic git commands and understand why we need version control.
- get familiar with conda environment and jupyter notebook
- manage to log in to the lab server.

## Linux Commands for Beginners
If you are not familiar with Linux, don't worry:) it is just like any other operating systems.

Some very basic commands are provided in [file](./linux-commands-for-beginners.pdf)

You can try whatever you want in the linux terminal and finish some very simple tasks listed below.

(Don't worry about killing the machine---it is a virtual machine, you can always start over. 

## Git and github

## Environment Preparation
You need to create a new conda environment to install all the package mentioned above and later set it as a jupyter kernel.

In the Linux terminal, run

- `conda create --name colab_env python==3.8`
- `conda activate colab_env`
- `pip install ipython ipykernel jupyterlab`
- `pip install numpy matplotlib nglview`
- `python -m ipykernel install --user --name colab_env --display-name "colab_env"`
- `jupyter lab --ip=0.0.0.0 --allow-root`

You will see a new website popping up.
- enter the token from the terminal (the token after token=) e.g.

    - from `http://127.0.0.1:8888/lab?token=5cebb31deb2683d53c7f25fc56643ba14c06bdbac9e2774d` enter `5cebb31deb2683d53c7f25fc56643ba14c06bdbac9e2774d`
    
- select the kernel `colab_env`

## Jupyter Notebook
- https://github.com/ipython/ipython-in-depth

**VOILÀ**

[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-908a85?logo=gitpod)](https://gitpod.io/#https://github.com/yuxuanzhuang/bioinformatics_alphafold)
