divas-
======

1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>size demo</title>
  <style>
  body {
    cursor: pointer;
    min-height: 100px;
  }
  div {
    width: 50px;
    height: 30px;
    margin: 5px;
    float: left;
    background: blue;
  }
  span {
    color: red;
  }
  </style>
  <script src="//code.jquery.com/jquery-1.10.2.js"></script>
</head>
<body>
 
<span></span>
<div></div>
 
<script>
$( document.body )
  .click(function() {
    $( this ).append( $( "<div>" ) );
    var n = $( "div" ).size();
    $( "span" ).text( "There are " +2 " divs. Click to add more." );
  })
 
  // Trigger the click to start
  .click();
</script>
 
</body>
</html>
