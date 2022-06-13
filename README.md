# JAGA
This repository contains the code and resources needed to build the machine learning model of Bangkit's capstone project team (C22-PS160), named JAGA.

# About
JAGA is Indonesian word for protection or take care.
**JAGA** is an application that aims for preventing female violence, we want to give assurance to the users, that they are protected by using this application.

# Repositories

|   Learning Paths   |                                Link                    |
| :----------------: | :----------------------------------------------------: |
| Mobile Development | [Github](https://github.com/RizaniHusyairi/JAGA)       |
|  Machine Learning  |  [Github](https://github.com/fnnysalsabilaa/JAGA)      |
|   Cloud Computing  |   [Github](https://github.com/indiramaretta/JAGA-API)  |

# Steps to Build Crime Prediction Model
1. Open Jupyter or Google Colaboratory notebook
2. Load the datasets: 
https://docs.google.com/spreadsheets/d/18dw98T17Lo9k_hJz7thZwUlpntjpIjdW1gl2yyXrKCA/edit?usp=sharing 
3. Exploratory Data Analysis (missing values detection, charts display)
   - Pre-Processing Datasets, including:
   - Min-max scaling longitude and latitude features
   - Checking and adding the missing features 
   - One-hot encoding year, hour, day, and month features 
   - Defining target (‘category’) and features from existing CSV file
   - Balancing datasets with imblearn.over_sampling module
   - Splitting datasets into training and validation data
4. Model Training (CatBoost, XGB, LightGBM, LGB Dart)
5. Testing Process: in order to properly predict the categories of the testing set with the ML model, we have to apply the same processing steps we performed so as to have the same features and distributions.
6. Save the Model after training into .h5, .py, .mdl, or .pkl file format and convert it into TensorFlow Lite format which has a .tflite file format extension.
