## PhoneNow Customer Retention Analysis | Pwc Switzerland Case Experience

### 📂 Background Information

- **Problem** : Customers in the telecom industry are hard-earned, in this case for PhoneNow. Churning customers using PhoneNow services were got in touch after they have terminated the contract, and the Customer Retention manager wants to understand their customer profile and insights with a focus on retaining customers as well as approaching in advance who is at risk.

- **Objectives** : The main objective of this task is to define proper KPIs and create a dashboard for the Call Centre Manager about customer retention reflecting the KPIs.

### 📂Tools 
Power BI 

### 📂 Dataset
The dataset used for this analysis was provided by Pwc Switzerland.

Dataset column:
| Field Name | Description | Data Type |
| --- | --- | --- |
| customerID | ID Customer | Text  |
| gender | Gender of the customer | Text (female, male) |
| SeniorCitizen | the customer is a senior citizen or not | Numeric (1,0)|
| Partner | the customer has a partner or not | Text (Yes,No) |
| Depentdents | the customer has dependents or not | Text (Yes,No) |
| Tenure | The duration (in month) as a customer in the company | Numeric |
| PhoneService | the customer has registered a phone service or not | Text (yes, no)|
| MultipleLines | the customer has multiple lines or not | Text(Yes, No, No phone service)|
| InternetService | Customer’s internet service provider | Text (DSL, Fiber optic, No) |
| OnlineBackup | the customer has online backup or not | Text(Yes, No, No internet service)|
| DeviceProtection | the customer has registered for device protection or not | Text(Yes, No, No internet service)|
| TechSupport |  the customer has tech support or not | Text(Yes, No, No internet service) |
| StreamingTV | the customer has streaming TV or not | Text(Yes, No, No internet service)|
| StreamingMovies | the customer has streaming movies or not | Text (Yes, No, No internet service) |
| Contract | The contract term of the customer | Text(Month-to-month, One year, Two year)|
| PaperlessBilling |  the customer has paperless billing or not | Text(Yes, No)|
| PaymentMethod | the payment method of the customer | Text  (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))|
| MonthlyCharges | the monthly charge incurred by the customer | Decimal number|
| TotalCharges | The total amount charged to the customer | Decimal number|
| numAdminTickets | the number of admin tickets opened by the customer | numeric |
| numTechTickets | the number of tech tickets opened by the customer | numeric |
| Churn | Whether the customer churned or not |Text (Yes or No)|


### 📂 Dashboard

![task3-1](https://github.com/windipngsti/PWC-Data-analytics/assets/133766866/ab7aa201-7637-4784-a6e0-f55b15a1782a)
| --- |
![Customer retention (1)-1](https://github.com/windipngsti/PWC-Data-analytics/assets/133766866/d0270a8a-072e-4856-841c-27150876032e)
| |

About Churned Customer Profile:

- Number of churned customers
- Retention & Churn Rate
- Total Admin & Tech ticket
- Total and monthly charge
- Demographic info
- Customer Account and Service info

About Customer risk analysis:

- Churn rate
- Churn by internet service
- Churn by payment method
- Churn rate vs tenure
- Total Admin & Tech tickets of churn customers
