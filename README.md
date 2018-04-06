
# Overview:
The objective of this competition is to build a model, learned using historical data, that will determine an employee's access needs, such that manual access transactions (grants and revokes) are minimized as the employee's attributes change over time. The model will take an employee's role information and a resource code and will return whether or not access should be granted.

Performance summary: The test AUC of my best model achieved 0.895. Tried three different feature engineering/selection techniques (ex. one-hot encoding, filtering unimportant features). Used a hyperparameter search algorithm Tuned 3 different types of models (ex. logistic regression, random forests). Experimented with ensembling and one meta-ensembling method which combines the classifiers I created
