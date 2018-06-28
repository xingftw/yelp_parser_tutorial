# yelp_parser_tutorial

**Week 1:**

1. requests.get(url) to get and then print the html of: https://www.yelp.com/biz/sweetwater-brewing-company-atlanta

2. then use bs4 Beautiful Soup to get specific parts of the html and print a single review description

  Hints:
  
  ```
  parsed_content = soup(url_content)
  container = parsed_content.find('script', {"type":"application/ld+json"})
  ```
