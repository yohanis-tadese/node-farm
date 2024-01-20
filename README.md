<body style="font-family: Arial, sans-serif; line-height: 1.5; margin: 2rem;">
  <h1 style="font-size: 1.5rem; margin-bottom: 1rem; text-align: center;">NODE-FARM</h1>
  <img src="./images/MainPage.png" alt="mainpage">

  <p style="line-height: 1.5;">This is a project that demonstrates a simple server-side application using Node.js and HTTP. The application reads data from a JSON file, generates HTML templates, and serves them to the client based on the requested URL.</p>

  <h3 style="font-size: 1.5rem; margin-bottom: 1rem; text-align: center;">Product Page</h3>
  <img src="./images/Product.png" alt="productpage">
  <h2 style="font-size: 1.2rem; margin-bottom: 0.5rem;">Project Structure</h2>

  <p style="line-height: 1.5;">The project consists of the following modules and files:</p>

  <ul>
    <li><strong>Modules:</strong>
      <ul>
        <li><code>fs</code> - provides file system-related functionality.</li>
        <li><code>http</code> - provides HTTP server and client functionality.</li>
        <li><code>url</code> - provides URL parsing and formatting.</li>
        <li><code>slugify</code> - a module for converting strings into URL-friendly slugs.</li>
        <li><code>replaceTemplate</code> - a custom module for replacing placeholders in HTML templates.</li>
      </ul>
    </li>
    <li><strong>Server:</strong>
      <ul>
        <li><code>data.json</code> - a JSON file containing product data.</li>
        <li><code>template-overview.html</code> - an HTML template for the overview page.</li>
        <li><code>template-card.html</code> - an HTML template for the product cards.</li>
        <li><code>template-product.html</code> - an HTML template for the individual product page.</li>
        <li><code>index.js</code> - the main server file.</li>
      </ul>
    </li>
  </ul>

  <h2 style="font-size: 1.2rem; margin-bottom: 0.5rem;">Usage</h2>

  <p style="line-height: 1.5;">To run the project, follow these steps:</p>

  <ol>
    <li>Install Node.js if you haven't already.</li>
    <li>Clone the repository or download the project files.</li>
    <li>Open a terminal in the project directory.</li>
    <li>Run the following command to install the required dependencies:</li>
  </ol>

  <pre><code>npm install</code></pre>

  <ol start="5">
    <li>Run the following command to start the server:</li>
  </ol>

  <pre><code>npm start</code></pre>

  <p style="line-height: 1.5;">Open a web browser and navigate to <code>http://localhost:8000</code> to access the application.</p>

  <h2 style="font-size: 1.2rem; margin-bottom: 0.5rem;">Routes</h2>

  <p style="line-height: 1.5;">The server handles the following routes:</p>

  <ul>
    <li><code>/</code> or <code>/overview</code>: Displays the overview page with all the product cards.</li>
    <li><code>/product?id={productId}</code>: Displays the individual product page for the specified product ID.</li>
    <li><code>/api</code>: Returns the raw JSON data.</li>
  </ul>

  <h2 style="font-size: 1.2rem; margin-bottom: 0.5rem;">Examples</h2>

  <p style="line-height: 1.5;">Here are a few examples to demonstrate how the routes work:</p>

  <ul>
    <li>Overview page: <a href="http://localhost:8000" style="color: blue;">http://localhost:8000</a> or <a href="http://localhost:8000/overview" style="color: blue;">http://localhost:8000/overview</a></li>
    <li>Product page for ID 1: <a href="http://localhost:8000/product?id=1" style="color: blue;">http://localhost:8000/product?id=1</a></li>
    <li>Product page for ID 2: <a href="http://localhost:8000/product?id=2" style="color: blue;">http://localhost:8000/product?id=2</a></li>
    <li>API data: <a href="http://localhost:8000/api" style="color: blue;">http://localhost:8000/api</a></li>
  </ul>

  <p style="line-height: 1.5;">Note: Please make sure to have the necessary data and template files in the correct locations as specified in the project structure. Adjust the code accordingly if you need to modify the file paths.</p>

  <p style="line-height: 1.5;">Feel free to explore and modify the code to suit your needs. Happy coding!</p>
</body>
