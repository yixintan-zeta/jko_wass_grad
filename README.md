# jko_wass_grad

This repository contains the implementation for the paper "Convergence of Flow-Based Generative Models via Proximal Gradient Descent in Wasserstein Space." We provide numerical evidence to support Assumption 1 in the paper, which posits the smallness of the Wasserstein gradient.

##Repository Contents##

The repository includes the following documents:

1. jko_gradient.py: This script contains functions necessary to estimate the Wasserstein gradient.

2. jko_wass_gead.ipynb: A Jupyter Notebook that can be used to reproduce the results presented in the paper. Simply run all the cells in order.

##Prerequisites##
The only package required to run the code is POT, which is used to estimate the optimal transport between two distributions. Additionally, the kernel estimation method is used to estimate the score function of a density given samples drawn from it.

##Installation##
To install the necessary package, run:
'''
pip install POT
'''
