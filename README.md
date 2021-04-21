# Gas Prices:
## Will They Stay or Will They Go...Up or Down

by Jacob Ash and Zachary Greenberg

<p align="center"><img src="https://github.com/zachagreenberg/OilPrices/blob/main/Images/Fuel_Pump_Image.png" width="400" height="250" /></p>

# Overview
Gas Prices have a history of change over time. This project aims to be one step ahead and accurately capture these changes for a calendar year. Being able to see this information can help people make informed decisions on their future financial planning. Our results were determined through the utilization of data from the EIA Open Data API as well as various additional sources. 

# Business Problem
Gas prices directly affect drivers everywhere. The rise of gas prices will financially impact their decisions and budgetary allowances, possibly restricting travel opportunities. With the ability to estimate future pricing, this could give individuals as well as transportation companies information so that they can plan ahead and account for any rise or decline.

# Data
Our data was taken from a combination of resources including the EIA Open Data API, Federal Reserve Economic Data, and Matteo Iacovello's Geopolitical Risk Index dataset. We have compiled our dataset from these resources, searching for the history of gas prices over time as well as other factors that are thought to influence the prices themselves. Here is a compiled list of the variables:

**Target**: RETAIL_GAS_PRICE - All Grades of Gasoline, U.S. City Average Retail Price, Monthly (Dollars per Gallon with Taxes)  
REGULAR_GAS_PRICE - U.S. Regular All Formulations Retail Gasoline Prices, Monthly (Dollars per Gallon)  
PREMIUM_GAS_PRICE - U.S. Premium All Formulations Retail Gasoline Prices, Monthly (Dollars per Gallon)  
EUROPE_BRENT - Europe Brent Spot Price FOB, Monthly (Dollars per Barrel)  
WTI - Cushing, OK WTI Spot Price FOB, Monthly (Dollars per Barrel)  
OIL_SUPPLY - U.S. Supply Adjustment of Crude Oil and Petroleum Products, Monthly (Thousands Barrels)  
CRUDE_OIL_PRODUCTION - Crude Oil Production, 48 States, Monthly (Thousands Barrels per Day)  
EMPLOYEES_OIL_EXTRACTION - Employees in US Oil, Monthly (Thousands of Persons)  
IMPORTS - Petroleum Imports, Annually (Millions of Barrels Per Day)  
FEDERAL_GAS_TAX - Excise Taxes on Gasoline, Annually (Billions of Dollars)  
STATE_GAS_TAX - State Government Sales Tax on Gasoline, Annually (Billions of Dollars)  
INFLATION - Inflation in Consumer Prices, Annually (Percent)  
GPR_MEXICO:GPR:COLOMBIA - Geopolitical Risk Index, Monthly, (Scale 0 to 600)