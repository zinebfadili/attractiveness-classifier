# Algorithmic fairness - Fairness in Computer Vision : Building an Attractiveness Classifier
Repository for the source code, the report and the poster for the project n°26a of the 02456 Deep Learning Course @ Technical University of Denmark.

## Project Description
*Deep Learning methods achieve impressive results on all types of tasks. However, when they fail, they often fail in a somewhat systematic way, creating and or amplifying existing social biases. The relatively young and quickly emerging field of Algorithmic Fairness investigates such issues, providing metrics to measure an algorithm's "fairness" and suggests ways to alleviate the potential societal impacts of such systematic failture of ML Systems.*

This project investigates whether a bias can be demonstrated for protected attributes such as gender and age when predicting attractiveness level. This project works with the CelebA dataset: image classification using CNN.
If and when a bias is identified, potential methods for alleviating it are developed and evaluated.

Steps include:
- Pre-processing the dataset
- Building a Neural Network and tweaking its performance
- Identifying potential biases and picking a proper fairness metric
- Implementing fixes if the algorithm turns out to be unfair and re-evaluating it

**This project was proposed by Pola Schwöbel, posc@dtu.dk and Cilie W. Feldager, cife@dtu.dk**

## Remarks
The source code is in a Jupyter Notebook, and the data is not added here. To run the notebook, change the paths to your drive where you have stored the data.

The .pth files contain the trained models (with and without data) that can be loaded so as not to retrain the model, they are too voluminous so here is the link to download them : https://drive.google.com/drive/folders/1dqvR1g0aRgrdphttaGt2W-4UTqcxeO9k?usp=sharing

*Note: Some results might differ between the notebook and the poster because we re-trained the model after the presentation.*

## Contributors
Zineb Fadili (s201501) & Victor Célérier (s201836)


