# level 03
## Description
http://www.pythonchallenge.com/pc/def/linkedlist.html
<br>

It says linkedlist.php so we replace lnkedlist.html to linkedlist.php
<br>
<a herf= "http://www.pythonchallenge.com/pc/def/linkedlist.php" > http://www.pythonchallenge.com/pc/def/linkedlist.php</a>

<br>

<a href="linkedlist.php?nothing=12345"><img src="http://www.pythonchallenge.com/pc/def/chainsaw.jpg" border="0"/></a>

<br>
 When we click the image it will redirect us to :<a herf= "http://www.pythonchallenge.com/pc/def/linkedlist.php?nothing=12345 " > http://www.pythonchallenge.com/pc/def/linkedlist.php?nothing=12345 </a> <br>

 And it is written <br>
 <I>and the next nothing is 44827</I>

## Solution

So we click view source and check the commented part : <br>
 It says:
 <br>

"urllib may help. DON'T TRY ALL NOTHINGS, since it will never 
end. 400 times is more than enough."
 <br>

So according to the statement solution is to replace the nothing= query in the url with next nothng that is given ,and repeat this process exactly 400 times.  <br> 

For example: <br>
When we click the image the current nothing is 12345 which is found in the url and the next nothing is 44827, so we need to replac the 12345 to 44827 in the url changing it to <a herf= "http://www.pythonchallenge.com/pc/def/linkedlist.php?nothing=44827 " > http://www.pythonchallenge.com/pc/def/linkedlist.php?nothing=44827</a> and so on... <br>
<br>

To solve this we need the help of urllib library create a function according to our codition <br>
 <br>
 So after passing 12345 as nothing and then going on loop for 400 times the next nothing came out to be : 16044 and when we update this on url, that is <a herf= "http://www.pythonchallenge.com/pc/def/linkedlist.php?nothing=16044 " > http://www.pythonchallenge.com/pc/def/linkedlist.php?nothing=16044</a> it says <br>
 "Yes. Divide by two and keep going."
 <br>
 So we divide 16044 by 2 which is 8022 and use this as our next nothing and now pass this in our function for 400 times which gave us our next nothing as 66831 <br>
 Now replace is as next nothing in url.

After xhanging url to nothing =66831 that is, <a herf= "http://www.pythonchallenge.com/pc/def/linkedlist.php?nothing=66831 " > http://www.pythonchallenge.com/pc/def/linkedlist.php?nothing=66831</a> it says 'peak.html' <br>
Now replace it on  url <br>

Go to  http://www.pythonchallenge.com/pc/def/peak.html
for level 5