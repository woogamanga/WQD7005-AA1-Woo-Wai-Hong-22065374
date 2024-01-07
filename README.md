Data mining in e-commerce involves extracting valuable insights and patterns from large datasets to enhance decision-making processes within online retail environments. The benefits of data mining in e-commerce include improved customer segmentation, personalized recommendations, and optimized marketing strategies based on historical customer behaviour. Customer churn prediction is particularly crucial in e-commerce as it helps identify customers at risk of leaving, allowing businesses to implement targeted retention strategies and ultimately enhance customer loyalty and profitability.
# WQD7005-AA1-Woo-Wai-Hong-22065374
Repository for Resources used in WQD7005 AA1 Woo Wai Hong 22065374
* customer_data.csv = Customer data 
* sales_data.csv = Sales data
* integrated_ecom.csv = Integrated E-Commerce Data after integration using Talend DI
* integrated_ecom2 Preparation.tde = sample data preprocessing using Talend DP
* Combine_Two_Files_AA1.zip = sample workflow for data integration in Talend DI
* 7005 AA1 Woo Wai Hong 22065374.spk = exported model package for SAS Enterprise Miner
* Resources.zip = resource folder containing screenshots of all the deliverables
## Objectives of AA1
The objectives for AA1 are as follows:
1.	To understand the distribution of key attributes in the synthetic dataset created which will inform relevant data preprocessing steps needed.
2.	To predict customer churn in the e-commerce domain using tree-based classifiers. 
3.	To determine the best performing tree-based classifier for the use case of customer churn classification in the e-commerce domain.
4.	To improve my mastery over the use Talend Data Integration (DI), Talend Data Preparation (DP) and SAS Enterprise Miner (EM) tools in conducting an end-to-end data mining project for AA1 using the SEMMA methodology.
## Role of Talend Data Integration (DI)
![image](https://github.com/woogamanga/WQD7005-AA1-Woo-Wai-Hong-22065374/assets/83159228/bd871e89-4055-48c7-9e6d-3ba766c8c9a2)

Talend Data Integration is an open-source ETL (Extract, Transform, Load) tool that enables organizations to connect, transform, and integrate data from various sources to meet their business needs.

The role of Talend DI in this assessment are as follows:
1.	To perform data integration on the 2 synthetic datasets, sales_data.csv and customer_data.csv, using tools in Talend DI such as ‘tFileInputDelimited’, ‘tMap’, ‘tFileOutputDelimited’. 

## Role of Talend Data Preparation (DP)
![image](https://github.com/woogamanga/WQD7005-AA1-Woo-Wai-Hong-22065374/assets/83159228/368ac21c-3a36-4239-b5f9-abaddbd21d5d)

Talend Data Preparation is a user-friendly, self-service data preparation tool that empowers business users to clean, enrich, and transform raw data into actionable insights, facilitating efficient data management and analysis.

The role of Talend DP in this assessment are as follows: 
1.	To perform data cleaning on the integrated synthetic dataset which has inconsistencies in columns such as ‘LastPurchaseDate’, ‘Gender’ and ‘Location’.

## Role of SAS Enterprise Miner (EM)
![image](https://github.com/woogamanga/WQD7005-AA1-Woo-Wai-Hong-22065374/assets/83159228/92c0b00a-dadf-4a9f-83d0-0839429260b3)

SAS Enterprise Miner is an advanced analytics and data mining tool that empowers organizations to build, deploy, and refine predictive models, uncover patterns in data, and make informed, data-driven decisions.
The role of SAS EM in this assessment are as follows: 
1.	To perform data preprocessing by means of mode imputation of the column ‘Returns’ which has missing values.
2.	To perform data preprocessing by means of dropping columns which are irrelevant to the analysis.
3.	To perform exploratory data analysis in order to understand the underlying distribution of the key attributes in the integrated dataset.
4.	To partition the integrated dataset into training, validation, and test sets in preparation for modeling using tree-based classifiers. 
5.	To train 3 tree-based classifiers to perform classification of e-commerce customer churn. 
6.	To evaluate the performance of the 3 tree-based classifiers using various performance metrics in order to determine the best performing classifier for the classification of customer churn in the e-commerce domain. 

