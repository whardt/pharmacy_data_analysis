# How much will your prescription drugs cost? - Predicting copayments with machine learning

This is a repository that hosts the excutive summary and code for the Fall 2022 Erdos Institute Bootcamp project. 

## Project Description
When a patient is prescribed medication from healthcare providers, their net copayment at the end of the transaction is determined by a complex system involving specific drug treatments, insurance, and other pharmaceutical factors. Currently, patients and doctors do not have a method of checking expected costs before prescribing medication. Machine learning presents considerable opportunities to improve patient-facing drug recommendations. In this project, we survey many regressors for predicting copayment costs based on patient insurance plans, available pharmacies, and the nature of possible medication details. With this, we hope to build the foundations for future systems that will inform doctors and patients about potential costs of medication before prescription to help patients work with doctors to find affordable treatment for their condition(s)medication. Details are documented in [ADD LINK TO THE EXECUTIVE SUMMARY]

## The Dataset (provided by [CoverMyMed](https://www.covermymeds.com/main/))
The dataset is composed of simulated transactions (n = 13910244) from different pharmacies that were taken across a single year. It includes the following features:
* 'tx_date': the date on which the pharmacy transaction was attempted
* 'pharmacy': the particular pharmacy where the transaction was attempted
* 'diagnosis': the diagnosis of the patient associated with the transaction
* 'drug': the drug that the patient was prescribed that the pharmacy is attempting to bill
* 'bin': the broadest identifier of a patient’s insurance plan (banking identification number)
* 'pcn': an identifier that more narrowly specifies a plan underneath the broader "bin"
* 'group': another identifier that more narrowly specifies a plan underneath the broader "bin"
* 'rejected': whether the billing transaction was rejected by the plan
* 'patient_pay': the amount of copayment for which the patient is responsible

## Technical Overview 

## Requirements 
The main packages include the following: numpy, pandas, matplotlib, seaborn, scikit-learn, GridSearchCV, DecisionTreeRegressor, RandomForestRegressor, AdaBoostRegressor, GradientBoostingRegressor, PolynomialFeatures, and LinearRegression

## Results

## Contact
Will Hardt: hardtwill@gmail.com

Karan Srivastava: linkedin.com/in/ksrivastava1/

Christine Sun: christine.l.sun@gmail.com

Funing Tian: fning.tian@gmail.com

