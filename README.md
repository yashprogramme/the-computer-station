<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box;}
body {font-family: Verdana, sans-serif;}
.mySlides {display: none;}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 350px;
  position: relative;
  margin: auto;
}


h3  { text-align: center;
    color: darkblue;
    font-weight: lighter;
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}
</style>
</head>
<body background="C:\Users\hp\Downloads\bg.png">



<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQEe1gnBJ0jT28VRO_htT814vg44eWReFV8_g&usqp=CAU" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSDb9Zg7IsaJTbAHvHXnGXwTBnhVMdw3qq03g&usqp=CAU" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRzTuF2SGyr8oeByOdapPkMSJbzrwfKVL9waQ&usqp=CAU" style="width:100%">
</div>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<script>
let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</script>
 <h3>Web development service by yash</h3>

 <h2 style="color: yellow;font-weight: lighter;">DYNAMIC websites by live web designer yash _ </h2>

 <p>Get websites at cheap price </p>
 <p>I offer various features such as dynamic web application </p>
 <p>Hosting websites for free</p>
 <p>providing free domain name for the websites</p>
 <br>
 <h3 style="margin-left: 10%"> All this features under rupees 300-500</h3>
 <div>
<img src="C:\Users\hp\Downloads\end.png" style="border-radius: 30%;">
<h4 style="position: absolute;margin-left: 30%; font-weight: lighter;color: orange;"><u>Three main dvantages of taking my service</u></h4>
<br><br>
<br>
<br><br>


<h5>1) My services are less costly then the market </h5>
<h5>2) My services are benefcial to my coustomer </h5>
<h5>3) You can change the design of website anytime </h5>
</div>

<style type="text/css">
  p{ color: black;
     font-weight: lighter;
  }
  h5{ color: green;
      font-weight: lighter;
      margin-left: 10%;

  }

 button {
  border: none;
  color: lightblue;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
  background-color: yellow;
  position: center;
  margin-left: 30%;
  
  }
</style>

<a href="affiliate.html"><button>GET STARTED</button></a>

</body>
</html> 
