# credit-risk-classification challenge


To assess loan(s) risk, lending companies will use machine learning to potentially discover a best assement for a consumers likeliness to repay debt are based upon many factors. Among those are historical lending data reported by other lenders to the various credit reporting agencies regarding the total number of open accounts, the total balance of current debt, total reported income and the debt to income ratio %. The CSV provided for this anaylsis provides 77536 records showing current active loans. Reviewing the provided csv shows the lowest loan value amount a is $5000 and the highest loan value is $23,800. 


## Analysis Overview

The pupose of this analysis is to use historical lending activity to evaluate loan risks based upon a set of data provided from a peer-to peer lending services company to indenify credit worthiness of a defined set of borrowers. The provided data set of 77536 records provided allows us to evaluate borrowers with a minimum loan value of $5000 to a maximum loan value of $23,80. The machine learning assigment is to predict if a loan is healthy indicated by a value of zero (0) or high-risk indicated by a value of one (1).

Employed anaylsis involves data preparation by separation between lables and features then splitting the data into testing and training sets. Logistic regression is used for the primary model, the model was finally evaluated for accuracy, precision of the data. 

## Results of analysis:

Loan Status(s):

-  (1) High-risk loans: 619 instances
-  (0) Healthy loans: 18,765 instances

Machine Learning Model 1:

- Accuracy: 99% (0.99)
- Precision (High-risk Loans (1)): 84% (0.84)
- Recall (High-risk Loans (1)): 89% (0.89)
- Precision (Healthy Loans (0)): 100% (1.00)
- Recall (Healthy Loans (0)): 99% (0.99)


## Summary

The logistic regression model shows strong predictivy among the high-risk (0 value) vs. heathy loan (1) value assesment based upon the classifiaction and confusion matirces. Healthy loans were predicted at 100% for accuracy, with a recall score lower by only 1%.

Predictivity between high-risk loans and healthy loans ratings offers an opportunity to discover the minimal risk loan classifications that could present potential lending opportunites that may be otherwise missed. 
