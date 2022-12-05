# NYC-Housing-Market-Forecasting
- author(s): Wen Lin, Xiaojin Li, Xin Huang, Yunyun Jin
- date created: Dec 1, 2022
- class: CIS 9440

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were:
1. For data integration - python
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

Motivation for project:
To understand the NYC housing market, especially relations between the new building permit request and house price. Our analytical work to be performed on the database will not only benefit the people that are in the real estate field but also those who are looking to purchase their primary home.


Description of the issues or opportunities the project will address:
The real estate industry is the backbone of NYC. The income generated from the sector is what made NYC today. Therefore those developers that see the opportunity will generate a high return. The Department of Building permit issuance and the NYC rolling sales show the number of new buildings and house prices, allowing us to determine the relationship between the two events. Along the way, we will learn the history of house prices in different boroughs and zip codes and the number of new building permit requests.


Project Business or Organization Value:
The analysis for the Construction of new structures of DOB permit will provide the
New York State Real Estate Development Corporation with a comprehensive view of a
specific residential or commercial property.
Combining historical permitted work with active building permits can assist the
company in accessing property risk, improving property valuations, uncovering home
services opportunities, and gaining a better understanding of a property.


Data Sources:
1.DOB NYC Permit Insurance
(link:https://data.cityofnewyork.us/Housing-Development/DOB-Permit-Issuance/ipu4-2q9a)
2.NYC Rolling Sales
(link:https://www.nyc.gov/site/finance/taxes/property-annualized-sales-update.page)


### Business Requirements Definition

List of Data Warehouse KPI's:
1.New Building Permits per Location( zip code, borough) 
2.New Building Permits per Building Type 
3.New Building Permits by Time(per year, month) 
4.Real Estate Price Change Percentage by Location
5.Median House Price by Location (zip code, borough) 


### Dimensional Model

This project's Dimensional Model consists of (x) Facts and (y) Dimensions

![Dimension model](/img/Dimension_model.jpg)

This project's Kimball Bus Matrix:

![Kimball bus matrix](/img/Kimball_BUS_Matrix.jpg)

### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Pie Chart for New Building Permits by Borough.
2. Horizontal Bar Chart for New Building Permits per Zip code.
3. Bar Chart for New Building Permits per Year.
4. Line Chart for New Building Permits per Month.
5. Geographic map for Rank of Median House Price in New York City
6. Box-and-Whisker Plot for Median Housing Price Distribution by Borough.
7. Bar plot for Real Estate Price Year Over Year Growth by Borough.
8. Bar plot for Real Estate Price Month Over Month Growth by Borough.
9. Dual Axis Combination Chart for New Building Permits vs Average Housing Price.


BI Application Wireframe design:

![Wireframe design-1](/img/BI_Wireframe_Design-1.jpg)
![Wireframe design-2](/img/BI_Wireframe_Design-2.jpg)
![Wireframe design-3](/img/BI_Wireframe_Design-3.jpg)

Picture of final Dashboard:

![Dashboard-1](/img/Dashboard-1.jpg)
![Dashboard-2](/img/Dashboard-2.jpg)
![Dashboard-1](/img/Dashboard-3.jpg)


### Deployment

The project was deployed on Tableau Public: https://public.tableau.com/app/profile/xiaojin.li/viz/NewBuildingPermitsKPIDashboard/Story1?publish=yes
 
