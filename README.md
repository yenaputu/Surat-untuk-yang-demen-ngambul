<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Kolase Romantis</title>
  <style>
    body {
      background-color: #fefefe;
      font-family: sans-serif;
      display: flex;
      justify-content: center;
      padding: 40px;
    }
    .collage {
      display: flex;
      flex-direction: row;
      gap: 20px;
      background: #fff;
      padding: 20px;
      border-radius: 20px;
      box-shadow: 0 8px 24px rgba(0, 0, 0, 0.15);
      position: relative;
    }
    .collage img {
      width: 300px;
      height: auto;
      border-radius: 12px;
      object-fit: cover;
    }
    .heart {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 48px;
      color: #ff6b81;
    }
  </style>
</head>
<body>
  <div class="collage">
    <img src="foto1.jpg" alt="Foto Romantis 1">
    <div class="heart">♥</div>
    <img src="foto2.jpg" alt="Foto Romantis 2">
  </div>
</body>
</html>