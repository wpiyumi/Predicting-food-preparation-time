# Predicting-food-preparation-time
Predicting food preparation time using Skip the Dishes data

### Data set
The data set was provided by "Skip the Dishes" for the Nexus data challenge. The training data set provides the order preparation time
in minutes, and the details of menu items included in eachorder. The training data set contains 80,000 records collected from 01-09-2019 to 07-09-2019.

Total of 114 features (90 menu items and 24 dummy variables that represent the hour of the order) were used for all the model implementations. The target variable was the food preparation time in minutes.

### Model fitting
Three models were implemented; a multiple linear regression model, a ridge regression model, and an artificial neural network (ANN) model (Multi-layer perceptron - MLP).
The model validation was carried out using 10-fold cross validation method.
