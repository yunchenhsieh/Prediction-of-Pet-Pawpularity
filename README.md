# Dogs vs. Cats Redux: Kernels Edition (Kaggle Competition)
# Project Description:

The primary objective is to accurately predict whether an image features a dog or a cat. It can guide shelters and rescuers 
around the world to improve the appeal of their pet profiles, automatically enhancing photo quality and recommending composition improvements 
For more details, visit https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/overview

# Dataset
The training data is composed of 25,000 images of dogs and cats, with labels embedded in filenames. 
The test set has 12,500 images identified by numeric IDs. 
The challenge is to predict the probability of an image being a dog (1 = dog, 0 = cat).

# Predictive Models
Experimentation involved two pre-trained models for binary classification:
1. VGG16
2. Xception

# Data Engineering
- Data Augmentation:
The goal of data augmentation is to increase the diversity of the training dataset, which can help improve the generalization and robustness of the machine learning model
1.Flip horizontally and vertically
2.Rotation: Rotating images by a certain degree
3.Brightness adjustment: Changing the brightness level of images
  
# Final Results 
The Xception model demonstrated superior performance with the lowest Kaggle score of 0.16845 among the two models. 
![image](https://github.com/yunchenhsieh/Prediction-of-Pet-Pawpularity/assets/168614090/717464a4-2507-457c-9f5f-211d4823c11e)
This result indicates the effectiveness of the Xception architecture for this specific classification task. 
Further details and code can be found in the project repository.

