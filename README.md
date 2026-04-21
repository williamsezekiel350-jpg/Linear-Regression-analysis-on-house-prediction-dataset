# Linear-Regression-analysis-on-house-prediction-dataset
A simple linear regression analysis to predict one variable based on another
1. Split the dataset
Before training, you must divide your data into a training set (to teach the model) and a testing set (to evaluate its accuracy on unseen data). A common split ratio is 80% for training and 20% for testing, which can be achieved using the train_test_split function. [4, 5, 6, 7] 
2. Fit the model
Using the training data, you "fit" the model to find the line that minimizes the difference between actual and predicted house prices. This is done by instantiating the LinearRegression() class and calling the .fit() method. [8, 9, 10, 11] 
3. Interpret coefficients and evaluate
Once the model is trained, you can analyze its performance using the following metrics:
Coefficients: These represent the change in the dependent variable (Price) for every one-unit change in an independent variable. For example, a coefficient of 150 for SquareFeet means each additional square foot adds roughly $150 to the house price.
R-squared ($R^2$): This score measures the proportion of variance in price that is predictable from the features. A score closer to 1.0 indicates a better fit.
Mean Squared Error (MSE): This measures the average squared difference between predicted and actual prices. Lower values indicate higher precision. [12, 13, 14, 15, 16, 17] 
Summary of Results
The model identifies the linear weight each feature contributes to the total house value. For instance, a high $R^2$ value (e.g., 0.90) would suggest that 90% of the price fluctuations are explained by the features you provided. [15, 16] 
Final Answer
The linear regression analysis provides a mathematical equation to predict house prices, where the R-squared score quantifies accuracy and the coefficients reveal the impact of each house feature on the final price.
