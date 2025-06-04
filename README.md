<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ONLINE MART</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }
    body {
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #1e3a8a;
      color: white;
      padding: 20px;
      text-align: center;
      font-size: 1.8rem;
      font-weight: 700;
    }
    .container {
      max-width: 1100px;
      margin: auto;
      padding: 20px;
    }
    .section-title {
      font-size: 1.5rem;
      margin: 40px 0 20px;
      color: #1e3a8a;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .product {
      background: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      text-align: center;
    }
    .product img {
      width: 100%;
      border-radius: 8px;
    }
    .product h3 {
      margin: 10px 0 5px;
      font-size: 1.1rem;
    }
    .product p {
      margin: 0 0 10px;
    }
    .order-btn {
      display: inline-block;
      padding: 10px 15px;
      background-color: #1e3a8a;
      color: white;
      border: none;
      border-radius: 5px;
      text-decoration: none;
      font-weight: 600;
    }
    footer {
      margin-top: 50px;
      padding: 20px;
      text-align: center;
      background-color: #f1f5f9;
      color: #555;
    }
  </style>
</head>
<body>
  <header>ONLINE MART</header>

  <div class="container">
    <div class="section-title">📱 Phone Gadgets</div>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/300x200?text=Phone+Holder" alt="Phone Holder" />
        <h3>360° Rotating Phone Holder</h3>
        <p>Rs. 1,990</p>
        <a class="order-btn" href="https://wa.me/94771234567?text=I%20want%20to%20order%20the%20360%20Phone%20Holder">Order via WhatsApp</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/300x200?text=Ring+Light" alt="Ring Light" />
        <h3>LED Selfie Ring Light</h3>
        <p>Rs. 2,450</p>
        <a class="order-btn" href="https://wa.me/94771234567?text=I%20want%20to%20order%20the%20LED%20Selfie%20Ring%20Light">Order via WhatsApp</a>
      </div>
    </div>

    <div class="section-title">💄 Beauty</div>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/300x200?text=Facial+Brush" alt="Facial Brush" />
        <h3>Facial Cleansing Brush</h3>
        <p>Rs. 2,200</p>
        <a class="order-btn" href="https://wa.me/94771234567?text=I%20want%20to%20order%20the%20Facial%20Cleansing%20Brush">Order via WhatsApp</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/300x200?text=Hair+Straightener" alt="Hair Straightener" />
        <h3>Mini Portable Hair Straightener</h3>
        <p>Rs. 1,850</p>
        <a class="order-btn" href="https://wa.me/94771234567?text=I%20want%20to%20order%20the%20Mini%20Hair%20Straightener">Order via WhatsApp</a>
      </div>
    </div>

    <div class="section-title">🏋️ Fitness</div>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/300x200?text=Resistance+Bands" alt="Resistance Bands" />
        <h3>Resistance Bands Set</h3>
        <p>Rs. 3,200</p>
        <a class="order-btn" href="https://wa.me/94771234567?text=I%20want%20to%20order%20the%20Resistance%20Bands%20Set">Order via WhatsApp</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/300x200?text=Digital+Jump+Rope" alt="Jump Rope" />
        <h3>Smart Digital Jump Rope</h3>
        <p>Rs. 2,700</p>
        <a class="order-btn" href="https://wa.me/94771234567?text=I%20want%20to%20order%20the%20Smart%20Digital%20Jump%20Rope">Order via WhatsApp</a>
      </div>
    </div>
  </div>

  <footer>
    © 2025 ONLINE MART | Contact us on WhatsApp +94714665751
  </footer>
</body>
</html>
