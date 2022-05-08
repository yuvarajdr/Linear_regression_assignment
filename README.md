# Linear_regression_assignment
> A US bike-sharing provider BoomBikes required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Essentially, the company wants
    - To identify Which variables are significant in predicting the demand for shared bikes.
    - To create a linear model that quantitatively relates How well those variables describe the bike demands
    - To know the accuracy of the model(target variable 'cnt' should be predicted with best model)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis of dataset below are considered as Categorical variables
    1. Season
    2. weathersit
    3. mnth
    4. weekday
    5. yr
- Conclusion 2 from the analysis
    - From observing the data set and dictionary we came to conclusion and categorical variable are as fallows:
      1.	Season : Target variable changes as season changes from spring to snow fall increasing manner and again decreases in winter
      2.	Weathersit : target variable dependence with comparison to weathersit is as fallows:
          Light_rain < mist_cloud < clean_cloud
      3.	Mnth : target variable changes(observe median) as we go from jan to mid of the year it increases then again after the sep we saw drastically decrease.
      4.	Weekday : there is no change in median its nearly constant but we can observe the difference in range and density which is more for Saturday and Wednesday.
      5.	Yr : due to corona company poor progress in 2018 and 2019 it got better

- Conclusion 3 from the analysis below are the best suited features for creating the model.
    - features and VIF are given below:
         1. atemp	      3.76
         2. windspeed	  3.73
         7. 2018	      1.84
         3. spring	    1.52
         5. mist_cloud	1.50
         6. jul	        1.27
         4. light_rain	1.06
         0. holiday	    1.03


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.10
- jupyter - version 2021.11

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad
- This project was based on Machine Learning model building using Linear regression


## Contact
Created by [@yuvarajdr](https://github.com/yuvarajdr) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
