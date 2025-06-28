<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>-</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      background-color: black;
      overflow: hidden;
    }
    iframe {
      width: 100vw;
      height: 100vh;
      border: none;
    }
  </style>
</head>
<body onload="launchFullscreen(document.documentElement)">
  <!-- 유튜브 영상 ID는 원하는 것으로 교체 -->
  <iframe
    src="https://www.youtube.com/embed/aU3PshgTxWc?autoplay=1&controls=0&showinfo=0&modestbranding=1&rel=0"
    allow="autoplay; fullscreen"
    allowfullscreen
  ></iframe>

  <script>
    // 전체화면 진입 함수
    function launchFullscreen(element) {
      if (element.requestFullscreen) {
        element.requestFullscreen();
      } else if (element.webkitRequestFullscreen) {
        element.webkitRequestFullscreen();
      } else if (element.mozRequestFullScreen) {
        element.mozRequestFullScreen();
      } else if (element.msRequestFullscreen) {
        element.msRequestFullscreen();
      }
    }
  </script>
</body>
</html>
