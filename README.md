# LITHVICK-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>LITHVICK | Services That Shine</title>
  <style>
    /* Reset & Font */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background: linear-gradient(135deg, red, orange, yellow, green, blue, indigo, violet);
      background-size: 400% 400%;
      animation: gradientMove 15s ease infinite;
      color: white;
      text-align: center;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    @keyframes gradientMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    header {
      padding: 80px 20px 40px;
    }

    header h1 {
      font-size: 3.5rem;
      letter-spacing: 2px;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 10px;
      opacity: 0.9;
    }

    section {
      background: rgba(255, 255, 255, 0.1);
      margin: 40px auto;
      padding: 30px;
      border-radius: 20px;
      width: 90%;
      max-width: 700px;
      backdrop-filter: blur(5px);
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 15px;
    }

    section p {
      font-size: 1rem;
      line-height: 1.6;
      opacity: 0.9;
    }

    .contact {
      margin-bottom: 60px;
    }

    .contact a {
      background: white;
      color: black;
      padding: 12px 30px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: 600;
      transition: all 0.3s ease;
    }

    .contact a:hover {
      background: black;
      color: white;
    }

    footer {
      padding: 20px;
      font-size: 0.9rem;
      opacity: 0.8;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2.5rem;
      }
      section {
        padding: 20px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>LITHVICK</h1>
    <p>Bright Ideas. Bold Solutions.</p>
  </header>

  <section>
    <h2>Our Services</h2>
    <p>
      At LITHVICK, we specialize in delivering creative and impactful services that help your brand stand out.
      From innovative business solutions to custom digital strategies, our goal is to bring color and energy
      to everything we do.
    </p>
  </section>

  <div class="contact">
    <a href="#contact">Contact Us</a>
  </div>

  <footer>
    © 2025 LITHVICK. All Rights Reserved.
  </footer>
</body>
</html
