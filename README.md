# Birthday-
<!DOCTYPE html>
<html>
<body>
  <div id="cake" onclick="boom()">🎂</div>
  <script>
    function boom() {
      document.body.innerHTML = `
        <h1 style="color:red;">生日快乐！</h1>
        <div style="font-size:100px;">💥${"❤️".repeat(100)}</div>
      `;
    }
  </script>
  <style>
    #cake { font-size: 100px; cursor: pointer; 
            animation: bounce 1s infinite alternate; }
    @keyframes bounce { 
      to { transform: scale(1.5); } 
    }
  </style>
</body>
</html>
