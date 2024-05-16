# Supervised Learning Challenge

In this challenge, we are taking the provided credit data to create a loan risk model.

## Creating variables
The provided csv file is imported and the loan status column is dropped and instead saved to a y variable. The remaining columns are kept as X.
![image](https://github.com/zhou0366/supervised_learning_challenge/assets/22827830/e3c3e420-7b36-4005-9d62-c5d9271b3db3)


![image](https://github.com/zhou0366/supervised_learning_challenge/assets/22827830/5cd438f0-a4c0-4837-a87d-2e125cab4b46)


## Model and Prediction
Using a random state of 1, a train_test_split is applied to our X and y variables. A logistic regression solver is applied to the training data which is then used to fit our model and generate a prediction. A confusion matrix and classification report for the prediction and test data. By looking at our classification report, we can see that the healthy loan label has a better prediction across all metrics.


![image](https://github.com/zhou0366/supervised_learning_challenge/assets/22827830/c1052e87-1dee-4018-b0b8-89c5a21ad749)

![image](https://github.com/zhou0366/supervised_learning_challenge/assets/22827830/1eedff83-7072-46bd-9d55-eb0e5cbc74aa)
