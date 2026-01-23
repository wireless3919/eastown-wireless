<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Eastown Wireless | Phone Repair</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: #f4f6f8;
            color: #222;
        }

        header {
            background: linear-gradient(135deg, #7b1fa2, #ff9800);
            color: white;
            padding: 30px 20px;
            text-align: center;
        }

            header h1 {
                margin: 0;
                font-size: 2.4rem;
            }

        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 14px;
            box-shadow: 0 6px 14px rgba(0,0,0,0.1);
            text-align: center;
        }

            .card h3 {
                color: #7b1fa2;
            }

        form {
            background: white;
            padding: 25px;
            border-radius: 14px;
            box-shadow: 0 6px 14px rgba(0,0,0,0.1);
            max-width: 500px;
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            border-radius: 8px;
            border: 1px solid #ccc;
        }

        button {
            margin-top: 15px;
            background: #7b1fa2;
            color: white;
            border: none;
            padding: 12px;
            border-radius: 25px;
            font-size: 1rem;
            cursor: pointer;
        }

        .cta {
            background: #7b1fa2;
            color: white;
            text-align: center;
            padding: 40px 20px;
        }

            .cta a {
                background: #ff9800;
                color: black;
                padding: 12px 24px;
                border-radius: 30px;
                text-decoration: none;
                font-weight: bold;
                margin: 5px;
                display: inline-block;
            }

        footer {
            background: #111;
            color: #ccc;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>

<body>

    <header>
        <h1>Eastown Wireless</h1>
        <p>📱 Fast • Reliable • Affordable Phone Repair</p>
        <p><strong>Call:</strong> <a href="tel:9372219804" style="color:white;">(937) 221-9804</a></p>
    </header>

    <section>
      <h2>Available Phones</h2>
      <div class="services">
        <div class="card">
          <h3>iPhones</h3>
          <p>Latest models available</p>
        </div>
        <div class="card">
          <h3>Samsung</h3>
          <p>All new Samsung phones</p>
        </div>
        <div class="card">
          <h3>Motorola</h3>
          <p>Affordable and reliable</p>
        </div>
      </div>
    </section>


    <section>
        <h2>Our Services</h2>
        <div class="services">
            <div class="card">
                <h3>Screen Repair</h3>
                <p>Fast screen replacement</p>
            </div>
            <div class="card">
                <h3>Battery Replacement</h3>
                <p>Battery life restored</p>
            </div>
            <div class="card">
                <h3>Charging Port Repair</h3>
                <p>Fix charging issues</p>
            </div>
            <div class="card">
                <h3>Water Damage</h3>
                <p>Professional diagnostics</p>
            </div>
        </div>
    </section>

    <section>
        <h2>Visit Our Store</h2>
        <p>
            <strong>Eastown Wireless</strong><br>
            3919 Linden Ave<br>
            Dayton, OH 45432<br>
            Phone: (937) 221-9804
        </p>
    </section>

    <section>
        <h2>Online Repair Booking</h2>
        <form name="repair-booking" method="POST" data-netlify="true">
            <input type="hidden" name="form-name" value="repair-booking">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="tel" name="phone" placeholder="Phone Number" required>
            <input type="text" name="device" placeholder="Device (iPhone, Samsung, etc.)" required>
            <textarea name="issue" rows="4" placeholder="Describe the issue" required></textarea>
            <button type="submit">Book Repair</button>
        </form>
    </section>

    <div class="cta">
        <h2>Need a Repair Today?</h2>
        <a href="tel:9372219804">📞 Call Now</a>
        <a href="https://www.facebook.com" target="_blank">📘 Facebook</a>
    </div>

    <footer>
        © 2026 Eastown Wireless. All rights reserved.
    </footer>

</body>
</html>
