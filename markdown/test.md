
<script>
function setHeader() {
var rand = Math.floor(Math.random() * 10);
switch (rand) {
case 0:
document.getElementById("pageHeader").style.backgroundImage = "url(http://www.rilab.org/images/image01.jpg)";
break;
case 1:
document.getElementById("pageHeader").style.backgroundImage = "url(http://www.rilab.org/images/image02.jpg)";
break;
case 2:
document.getElementById("pageHeader").style.backgroundImage = "url(http://www.rilab.org/images/image03.jpg)";
break;
case 3:
document.getElementById("pageHeader").style.backgroundImage = "url(http://www.rilab.org/images/image04.jpg)";
break;
case 4:
document.getElementById("pageHeader").style.backgroundImage = "url(http://www.rilab.org/images/image04.jpg)";
break;
case 5:
document.getElementById("pageHeader").style.backgroundImage = "url(http://www.rilab.org/images/image05.jpg)";
break;
case 6:
document.getElementById("pageHeader").style.backgroundImage = "url(http://www.rilab.org/images/image06.jpg)";
break;
case 7:
document.getElementById("pageHeader").style.backgroundImage = "url(http://www.rilab.org/images/image07.jpg)";
break;
case 8:
document.getElementById("pageHeader").style.backgroundImage = "url(http://www.rilab.org/images/image08.jpg)";
break;
case 9:
document.getElementById("pageHeader").style.backgroundImage = "url(http://www.rilab.org/images/image09.jpg)";
break;
default:
document.getElementById("pageHeader").style.backgroundImage = "url(http://www.rilab.org/images/image10.jpg)";
}
}

addLoadEvent(setHeader);

function addLoadEvent(func) {
  var oldonload = window.onload;
  if (typeof window.onload != 'function') {
    window.onload = func;
  } else {
    window.onload = function() {
      if (oldonload) {
        oldonload();
      }
      func();
    }
  }
}
</script>

## Stuff

* Other stuff

* More stuff

    - This is **my stuff**
