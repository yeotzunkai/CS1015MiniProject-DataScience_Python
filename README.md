# Mini-Project for SC1015 Introduction to Data Science and Artificial Intelligence
![alt text](https://github.com/yeotzunkai/CS1015MiniProject-DataScience_Python/blob/main/Images/Car.jpg "Source: https://www.bugatti.com/models/veyron-models/veyron-164-super-sport/")
---

### This repository consists of 3 main folders
###  - [Data Preparation and Exploratory Data Analysis Folder](https://github.com/yeotzunkai/CS1015MiniProject-DataScience_Python/tree/main/DSAI%20Project/Data%20Cleaning%20and%20Exploratory%20Data%20Analysis)
#### Notebooks of Data cleaning and EDA can be found here
###  - [Prediction Models folder](https://github.com/yeotzunkai/CS1015MiniProject-DataScience_Python/tree/main/DSAI%20Project/Model)
#### Notebooks of Exploring Prediction Models and Individual Prediction Models can be found here.
#### [Price_Predictor.ipynb](https://github.com/yeotzunkai/CS1015MiniProject-DataScience_Python/blob/main/DSAI%20Project/Model/Price_Predictor.ipynb)
#### Contains functions (predict(model,x,y)) to predict price of a 2020 Hyundai Elantra SE IVT (Values can be changed to predict other cars)
###  - [Dataset Folder](https://github.com/yeotzunkai/CS1015MiniProject-DataScience_Python/tree/main/DSAI%20Project/Dataset)
#### Original Data set and Cleaned Data set can be found here
---
## Problem Definition 
### 1. Are we able to predict a car price based on its features?
### 2. Which model would be the best to predict it?
---
## Predictive Models explored
### ⋅ Linear Regression
### ⋅ K-Nearest neighbours
### ⋅ Decision Tree
### ⋅ Random Forest 
### ⋅ Graph Boosting 
--- 
## Conclusion
#### Random Forest Regression was found to have higher accuracy in predicting car prices.
#### Brand and the year the car was manufactured have higher relationship with price.
#### There were not enough data points from luxury brands for training the model, which resulted in the model being unable to accurately predict the price of cars outside the range of the dataset used to train the model. 
#### The model is however still suitable for use when it comes to the majority of the people looking to buy or sell their cars. 

---
## References
#### https://machinelearningmastery.com/visualize-gradient-boosting-decision-trees-xgboost-python/
#### https://mljar.com/blog/visualize-tree-from-random-forest/
#### https://www.geeksforgeeks.org/how-to-convert-categorical-variable-to-numeric-in-pandas/amp/
#### https://towardsdatascience.com/how-to-visualize-a-decision-tree-from-a-random-forest-in-python-using-scikit-learn-38ad2d75f21c
#### https://www.statisticshowto.com/probability-and-statistics/hypothesis-testing/anova/
#### https://thinkingneuron.com/car-price-prediction-case-study-in-python/
#### https://www.datasciencecentral.com/how-to-choose-a-machine-learning-model-some-guidelines/amp/
#### https://towardsdatascience.com/predicting-car-price-using-machine-learning-8d2df3898f16
#### https://cars.usnews.com/cars-trucks/hyundai/elantra/2020
#### https://www.datacamp.com/community/tutorials/k-nearest-neighbor-classification-scikit-learn
#### http://shakedzy.xyz/dython/getting_started/examples/
---
### Contributors
#### 🤖 [twm2k](https://github.com/twm2k)
##### Did exploratory data analysis. Helped to clean dataset, make video and presentation slides
#### 🤖 [yeotzunkai](https://github.com/yeotzunkai)
##### Did modeling for dataset. Helped to clean dataset, make video and presentation slides
#### 🤖 [Zisuan](https://github.com/Zisuan)
##### Did modeling for dataset. Helped to clean dataset, make video and presentation slides
