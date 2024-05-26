# Random Forest (RF)

The Random Forest algorithm is a type of ensemble learning technique that builds upon the principles of
bagging, specifically with random feature selection. Unlike a single decision tree, Random Forest constructs
multiple decision trees during training. Each tree is trained on a bootstrapped sample of the training data, and
at each split of the tree, only a random subset of features is considered. In the case of classification tasks, these
predictions are combined through a voting mechanism, where the class with the most votes among all the trees
is selected as the final prediction. This random feature selection helps reduce the risk of overfitting the model
to the training data

The RF models were developed in Python to address the predictive task for brain stroke. Since, the dataset contains data imbalance issue, following analysis is performed:

* **Undersampling**: Reducing the majority class to match the minority class size to train the RF model.
* **Oversampling**: Increasing the minority class using techniques like SMOTE to match the majority class size to train the RF model.
