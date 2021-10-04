# Predicting-California-Housing-prices
An End to End machine learning project on California housing dataset, our task is to predict median house values in Californian districts,  given a number of features from these districts.

0) Load the housing data of 11 features(longitude, latitude, housing_median_age, total_rooms, total_bedrooms, population, households, median_income, median_house_value,    ocean_proximity)
  - explore the features and the correlation

1) Discover and visualize the data to gain insights :
	- create new features that correlate better with our response data
	- the response variable


2) Prepare the data for Machine Learning algorithms : 
	 - dealing with missing values & text features
	 - build a pipeline for preprocessing the numerical attributes


3) Select & train a model :
	- linear regression on our prepared data & our housing labels
	- evaluate the linear regression with mean squarred error
	- evaluate the decision tree regressor


4) Fine tune the model for :
	- the decision tree regressor 
	- RandomForestRegressor
	- SVR
	- gris search CV

