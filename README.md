# University-Admission-Prediction
A logistic regression model aiming to predict whether a candidate will be admitted by a university.

Grades of two exams and admission result of past candidates are given as training data. We will train a classifier from scratch to predict the admission probability of a certain candidate based on two exam scores.

The following methods are established:

-  `sigmoid` : maps to probability

-  `model` : returns probability result

-  `cost` : computes loss based on parameters

-  `gradient` : computes each parameter's gradient direction

-  `descent` : updates parameters

-  `accuracy`: computes accuracy on test set

Besides, I will also explore the behavior of gradient descent based on three different stop strategies.
