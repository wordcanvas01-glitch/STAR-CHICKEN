# STAR-CHICKEN<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Star Chicken | Albi</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
}

header {
    background: linear-gradient(rgba(0,0,0,.5), rgba(0,0,0,.5)),
                url('https://images.unsplash.com/photo-1513104890138-7c749659a591');
    background-size: cover;
    background-position: center;
    height: 100vh;
    color: white;
}

nav {
    display: flex;
    justify-content: space-between;
    padding: 20px 10%;
}

.logo {
    font-size: 2rem;
    font-weight: bold;
}

nav ul {
    display: flex;
    list-style: none;
    gap: 25px;
}

.hero {
    height: 80%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 20px;
}

.hero h1 {
    font-size: 4rem;
    margin-bottom: 15px;
}

.hero p {
    font-size: 1.3rem;
    margin-bottom: 20px;
}

.btn {
    background: #ffb000;
    color: black;
    padding: 15px 30px;
    text-decoration: none;
    border-radius: 30px;
    font-weight: bold;
}

section {
    padding: 80px 10%;
}

.section-title {
    text-align: center;
    margin-bottom: 40px;
    font-size: 2.5rem;
}

.menu-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    gap: 25px;
}

.card {
    background: #f7f7f7;
    padding: 25px;
    border-radius: 12px;
    text-align: center;
}

.card h3 {
    margin-bottom: 10px;
}

.price {
    color: #ff9800;
    font-weight: bold;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    gap: 15px;
}

.gallery img {
    width: 100%;
    border-radius: 12px;
}

form {
    max-width: 600px;
    margin: auto;
}

input, textarea {
    width: 100%;
    padding: 15px;
    margin-bottom: 15px;
}

button {
    background: #ffb000;
    border: none;
    padding: 15px 30px;
    cursor: pointer;
    border-radius: 30px;
}

footer {
    background: #111;
    color: white;
    text-align: center;
    padding: 25px;
}
</style>
</head>

<body>

<header>
<nav>
<div class="logo">Star Chicken</div>

<ul>
<li>Home</li>
<li>Menu</li>
<li>Gallery</li>
<li>Reservations</li>
<li>Contact</li>
</ul>
</nav>

<div class="hero">
<h1>Star Chicken</h1>
<p>Fresh. Crispy. Delicious.</p>
<a href="#reservation" class="btn">Reserve a Table</a>
</div>
</header>

<section id="menu">
<h2 class="section-title">Popular Menu</h2>

<div class="menu-grid">
<div class="card">
<h3>Classic Chicken Burger</h3>
<p>Crispy chicken, lettuce & sauce</p>
<p class="price">€7.90</p>
</div>

<div class="card">
<h3>Chicken Wrap</h3>
<p>Grilled chicken with fresh vegetables</p>
<p class="price">€6.90</p>
</div>

<div class="card">
<h3>Family Bucket</h3>
<p>12 pieces of crispy chicken</p>
<p class="price">€19.90</p>
</div>

<div class="card">
<h3>Loaded Fries</h3>
<p>Cheese, chicken & special sauce</p>
<p class="price">€5.90</p>
</div>
</div>
</section>

<section>
<h2 class="section-title">Our Restaurant</h2>

<p style="text-align:center; max-width:700px; margin:auto;">
Located in Albi, Star Chicken serves fresh, high-quality chicken meals in a modern and welcoming atmosphere. Perfect for families, friends and quick lunches.
</p>
</section>

<section>
<h2 class="section-title">Gallery</h2>

<div class="gallery">
<img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd">
<img src="https://images.unsplash.com/photo-1626082927389-6cd097cdc6ec">
<img src="https://images.unsplash.com/photo-1606755962773-d324e0a13086">
</div>
</section>

<section id="reservation">
<h2 class="section-title">Reservations</h2>

<form>
<input type="text" placeholder="Your Name">
<input type="email" placeholder="Email">
<input type="date">
<textarea placeholder="Special Request"></textarea>
<button type="submit">Book Now</button>
</form>
</section>

<section>
<h2 class="section-title">Contact</h2>

<p style="text-align:center;">
📍 Albi, France<br>
📞 +33 5 XX XX XX XX<br>
🕒 Open Daily: 11:00 - 23:00
</p>
</section>

<footer>
<p>© 2026 Star Chicken - Albi</p>
</footer>

</body>
</html>
