<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>X Auto Shop</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #111;
      color: white;
      line-height: 1.6;
    }

    header {
      background: #000;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #e63946;
    }

    header h1 {
      color: #e63946;
      font-size: 35px;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
    }

    .hero {
      padding: 80px 20px;
      text-align: center;
      background: linear-gradient(#0009, #0009), #222;
    }

    .hero h2 {
      font-size: 42px;
      margin-bottom: 15px;
    }

    .hero p {
      color: #ccc;
      margin-bottom: 25px;
    }

    .button {
      display: inline-block;
      background: #e63946;
      color: white;
      padding: 12px 25px;
      text-decoration: none;
      border-radius: 6px;
      font-weight: bold;
    }

    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }

    section h2 {
      text-align: center;
      margin-bottom: 30px;
      color: #e63946;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }

    .service {
      background: #1c1c1c;
      padding: 25px;
      border-radius: 10px;
      text-align: center;
      border: 1px solid #333;
    }

    .service h3 {
      margin-bottom: 10px;
    }

    .contact {
      text-align: center;
      background: #181818;
      max-width: none;
    }

    footer {
      background: #000;
      text-align: center;
      padding: 20px;
      color: #777;
    }
  </style>
</head>

<body>

  <header>
    <h1>X Auto Shop</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h2>Keep Your Ride Running Right</h2>
    <p>Professional auto service you can count on.</p>
    <a href="#contact" class="button">Contact Us</a>
  </div>

  <section id="services">
    <h2>Our Services</h2>

    <div class="services">
      <div class="service">
        <h3>Oil Changes</h3>
        <p>Fast and reliable oil changes for your vehicle.</p>
      </div>

      <div class="service">
        <h3>Brake Service</h3>
        <p>Brake inspections, repairs and replacements.</p>
      </div>

      <div class="service">
        <h3>Engine Repair</h3>
        <p>Professional engine diagnostics and repairs.</p>
      </div>

      <div class="service">
        <h3>Tire Service</h3>
        <p>Tire checks, rotations and replacements.</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>About X Auto Shop</h2>
    <p>
      X Auto Shop is dedicated to providing dependable automotive service
      and helping customers keep their vehicles running smoothly.
    </p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Call us to schedule your service.</p>
    <br>
    <a href="tel:5555555555" class="button">Call X Auto Shop</a>
  </section>

  <footer>
    <p>© 2026 X Auto Shop. All rights reserved.</p>
  </footer>

</body>
</html>