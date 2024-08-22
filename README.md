# Amazon Web Scraping

This project is a Python-based web scraping tool designed to extract product data from Amazon product pages. The script utilizes the `requests` library to fetch the content of a web page and `BeautifulSoup` to parse and extract specific data, such as the product title and price.

## Project Description

The script is capable of:

- **Extracting Product Title**: The script retrieves the product title from the Amazon product page by targeting the appropriate HTML element.
- **Extracting Product Price**: The script extracts both the whole and fractional parts of the product price. It then formats and combines these parts into a single, well-structured output.

### How It Works

1. **HTTP Request**: The script sends a request to the specified Amazon product URL and retrieves the HTML content of the page.
2. **HTML Parsing**: The retrieved HTML content is parsed using `BeautifulSoup`, which helps in navigating and searching the HTML tree structure.
3. **Data Extraction**: Specific HTML elements containing the product title and price are targeted using their `id` or `class` attributes. The script then extracts and formats the data for output.
4. **Output**: The script prints the product title and the formatted price to the console.

### Example Output

The output of the script might look like this:

```plaintext
OnePlus Nord CE 3 Lite 5G (Pastel Lime, 8GB RAM, 128GB Storage)
17,990.00
