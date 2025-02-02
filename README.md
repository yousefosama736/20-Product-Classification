# 20 Product Classification using InceptionV3

This project focuses on classifying 20 different product categories using the InceptionV3 model. The model is fine-tuned on a custom dataset, and the training process includes data augmentation, validation, and testing.

## Table of Contents
- [Overview](#overview)
- [Dependencies](#dependencies)

## Overview
The project uses the InceptionV3 model pre-trained on ImageNet, with the last 100 layers fine-tuned for the specific task of product classification. The dataset is split into training, validation, and test sets, and the model is trained using data augmentation techniques to improve generalization.

## Dependencies
To run this project, you need the following Python libraries:
- TensorFlow
- NumPy
- Matplotlib
- scikit-learn
- gdown
- rarfile
- patool

You can install the required dependencies using the following command:
```bash
pip install gdown rarfile patool tensorflow tflearn numpy matplotlib scikit-learn
