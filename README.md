## Nigeria-COVID-19-Data-Analysis-Using-Python
Data Scientist Microdegree Capstone Project

# Project Overview
This Project shows how COVID-19 is being investigated and to prevent, detect, and respond to the threat posed by COVID-19 at state level in Nigeria

#Project Steps

Step 1: The appropriate libraries were imported and data was scraped from the
Official NCDC Website

Libraries Imported

.matplotlib.pyplot
.warnings
.time
.BeautifulSoup from bs4
.seaborn
.requests
.numpy
.urllib.request
.pandas
.csv

Methods Used

.strip()
.find_all()
.append()
.reshape()
.read_html()
.time()
.get()
.Find()

Attributes Used

.content
Step 2: Data was extracted from the Josh Hopkins Data Repository

Methods Used

.read_csv()

Step 3: Data was extracted from external data sources

Methods Used

.read_csv()

Step 4: Data from Josh Hopkins Repository which contained global data was removed to Nigeria's data, columns was renamed from the NCDC data to another and special characters was removed from the numerical columns.

Methods Used

.apply()
.drop()
.rename()
.melt()
to_datetime()

Attributes Used

.columns

Step 5: Data Analyses is  performed and visualizations is created.

Methods Used

.diff()
.max()
.idmax()
.rename()
.replace()
.merge()
.twinx()
.corr()
.nlargest()
.color_palette()
.set_context()
.figure()
.title()
.xlabel & ylabel
.xticks & yticks
.abs()
.plot_relation()
.sum()
.legend()
.xlim & ylim
.axhline()
.max()
.idmax()
.rename()
.replace()
.merge()
.twinx()
.corr()

Attributes Used

.Date
.index

Plots Created

.pointplot
.heatmap
.pie
.regplot
.barplot
.lineplot

Expressions

.lambda expression

Presentation

 
