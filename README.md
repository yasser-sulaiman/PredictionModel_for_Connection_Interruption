# Prediction Model for Connection Interruption

This project has been done as a term project within the random noise and signals course.  
The aim of the project is to build a model to predict whether a subscriber will open a disconnection ticket or not in the next three days.  
The dataset has about 5 million example of subscribers from 81 different cities in Turkey.  
<br>
In order for the code to run without problems the following tools and libraries need to be installed:
* Python 3.7
* Jupyter notebook
* Pandas
* Numpy
* Matplotlib
* Collections
* Sklearn
* Openpyxl

# Data Preperation
Some data preparation cleaning has been done before training the model.
* Filling empty rows in targeted Column
* Filling some columns with dummy values
* Decreasing the difference between zeros and ones in targeted column
* Encoding the data


# Two Different Models
In this project I have tryed two different models and decided for one of them according to the outputs I got.


# The Confusion Matrix for The KNN Model Accuracy = 95.4%
![](https://github.com/yasser-sulaiman/PredictionModel_for_Connection_Interruption/blob/main/images/KNN_matrix.png)

# The Confusion Matrix for The MLP Model Accuracy = 99.7%
![](https://github.com/yasser-sulaiman/PredictionModel_for_Connection_Interruption/blob/main/images/MLP_matrix.png)
