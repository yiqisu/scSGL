# scSGL
Graph signal processing based signed graph learning for gene regulatory inference from single cell RNA-seq data as described in [1].

## Installation
Once you download the repo, go to the repo directory and start a terminal. First, create an 
environment and then install the required packages listed in `requirements.txt`. This can be done as
follows for conda:
```sh
conda create -n sgl python=3.8
conda activate sgl
```
This will create a conda environment. To install the requirments:
```sh
conda install -c conda-forge --file requirements.txt
```
This may take some time as it also installs R to conda environemnt. Finally, to be able to use 
zero inflated Kendall as a kernel, `pcaPP` R package need to installed as well. 

## Usage 
Please see `demo.ipynb` under notebooks folder for an illustration how to use code. 

## Datasets
An example dataset is given under data folder to be used demonstration notebook. For datasets used 
in the paper, please [BEELINE](https://github.com/Murali-group/Beeline). Datasets used for parameter
sensitivity will be published soon. 

## References
[1] [scSGL: Signed Graph Learning for Single-Cell Gene Regulatory Network Inference](https://www.biorxiv.org/content/10.1101/2021.07.08.451697v2.abstract)
