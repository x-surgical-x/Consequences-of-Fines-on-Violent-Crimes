## Python code to Scrape [FBI crimes data](https://www.ucrdatatool.gov/Search/Crime/Local/RunCrimeOneYearofData.cfm) website using [Selenium Webdriver](http://www.seleniumhq.org/projects/webdriver/)

### Requirements:
1. Selenium Webdriver for python.  
``` pip install -U selenium ```
2. BeautifulSoup for python.  
``` pip install beautifulsoup4 ```
3. Chrome Webdriver. [Download link](https://sites.google.com/a/chromium.org/chromedriver/downloads)

### Usage:
- `python scraper.py`
-  A new directory `fbi-crime-data` will be created and all the data(separate file for each state) be saved in that directory.
- The code dumps entire data(in csv format) from the FBI crime data website to the file.

#### Python selenium documentation can be found [here](http://selenium-python.readthedocs.io/).
