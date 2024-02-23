<!DOCTYPE html>
<html>
<head>
<title>BARAARUG</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="syst.css">
<style>
body,h1,h5 {font-family: "Raleway", sans-serif ,color #333131,}
body, html {height: 100%}
.bgimg {
  background-image: url(f8838b18ce265b478ef36e99f19ad4ffcdf86b86.jpeg);
  min-height: 100%;
  background-position: center;
  background-size: cover;
}
</style>
</head>
<body>
<H1>WELCOME AL HUDA UNIVERSITYS</H1>
<div class="bgimg -display-container -text-white">
  <div class="-display-middle -jumbo">
    <p></p>
  </div>
  <div class="-display-topleft -container -xlarge">
    <p><button onclick="document.getElementById('menu').style.display='block'" class="button w3-black">menu</button></p>
    <p><button onclick="document.getElementById('contact').style.display='block'" class="button w3-black">contact</button></p>
  </div>
  <div class="-display-bottomleft w3-container">
    <p class="-xlarge">monday - friday 10-23 | saturday 14-02</p>
    <p class="-large">Hargisa ,Somaliland </p>
    <p>COPYRIGHT BARAARUG.COM</p>

  </div>
</div>

<!-- Menu Modal -->
<div id="menu" class="w3-modal">
  <div class="-modal-content w3-animate-zoom">
    <div class="-container black display-container">
      <span onclick="document.getElementById('menu').style.display='none'" class="-button -display-topright -large">x</span>
      <h1>Starters</h1>
    </div>
    <div class="-container">
  
    </div>
    <div class="-container w3-black">
      <h1>Main Courses</h1>
    </div>
    <div class="-container">
      <h5>Healty secia <b>$200</b></h5>
      <h5>islamic  <b>$200</b></h5>
      <h5>ICT <b>$400</b></h5>
      <h5>Bussiencess and econamic <b>$250</b></h5>
    
    </div>
    <div class="-container w3-black">
      <h1>Facult of ICT</h1>
    </div>
    <div class="-container">
      <h5>NETWORKING<b></b></h5>
      <h5>WEBSITE <b></b></h5>
      <h5>IT-HARDWARD <b></b></h5>
      <h5>MATHEMATIC OF CALCULS <b></b></h5>
    </div>
    <div class="-container w3-black">
      <h1>Desserts</h1>
    </div>
    <div class="-container">
      <h5><b></b></h5>
      
  </div>
</div>

<!-- Contact Modal -->
<div id="contact" class="w3-modal">
  <div class="-modal-content -animate-zoom">
    <div class="-container -black">
      <span onclick="document.getElementById('contact').style.display='none'" class="-button -display-topright -large">x</span>
      <h1>Contact us</h1>
    </div>
    <div class="w3-container">
      <p>Reserve a table, ask for today's special or just send us a message:</p>
      <form action="/action_page.php" target="_blank">
        <p><input class="-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
        <p><input class="-input w3-padding-16 w3-border" type="text" placeholder="enter your email" required name="enter your email"></p>
        <p><input class="-input w3-padding-16 w3-border" type="number" placeholder="What can we do to help?
          " required name="People"></p>
        <p><input class="-input w3-padding-16 w3-border" type="datetime-local" placeholder="Date and time" required name="date" value="2020-11-16T20:00"></p>
        <p><input class="-input w3-padding-16 w3-border" type="text" placeholder="Message \ Which courses do you need?" required name="Message"></p>
        <p><button class="-button" type="submit">SEND MESSAGE</button></p>
      </form>
    </div>
  </div>
</div>

</body>
</html>