<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{margin: 0; padding: 0; color: #fff; box-sizing: border-box;}
        ul{list-style: none;}
        a{text-decoration: none; color: inherit;}
        a:hover{color: orange;}
        img{width: 320px; height: 420px; object-fit: cover}
        
        header{
            width: calc(1000px); height: 50px;
            margin: 0 auto;
            background-color: rgb(10, 10, 10);
            
        }
        .header-group{
            display: flex;
            justify-content: space-around;
        }
        .logo{
            font-size: 2rem;
            font-weight: 700;
        }
        .gnb-menu{
            display: flex;
            gap: 40px;
            align-items: center;
        }

        main{
            width: 1000px; margin: 0 auto;
            background-color: #2a2030;
        }
        .section1{
            display: flex;
            justify-content: space-around;
            align-items: center;
            padding-top: 50px;
        }
        .hero-description{
            margin: 30px 0px;
        }
        .menu-button{
            width: 100px; height: 40px;
            border: 1px solid #fff;
            background-color: #00000000;
            color: #fff;
            font-size: 1rem;
        }
        .section2{
            margin-top: 50px;
        }
        h2{
            margin-bottom: 20px;
        }

        .menu-img1{
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }
        .menu-img2{
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }
        .menu-img1>li{

            font-size: clamp(30pt, 4vw, 60pt); 
            line-height: 300px;
        }
        .menu-img2>li{

            font-size: clamp(30pt, 4vw, 60pt); 
            line-height: 300px;
        }

        footer{
            width: 1000px; margin: 0 auto;
            height: 50px;
            background-color: rgb(0, 0, 0);
            color: #fff; text-align: center;
        }

        @media (max-width:768px){
            img{width: 150px; height: 220px; object-fit: cover}
            header{
                width: 100%;
                height: 250px;
            }
            .header-group{
                flex-direction: column;
            }
            .logo{
                text-align: center;
                margin-bottom: 30px;
            }
            .gnb-menu{
                flex-direction: column;
            }
            main{
                width: 100%;
                background-color: #2a2030;
            }
            .section2{
                gap: 10%;
                padding: 0 1%;
            }
            footer{
                width: 100%;
                background-color: rgb(0, 0, 0);
            }
        }

    </style>
</head>
<body>
    <header>
        <div class="header-group">
            <p class="logo">Monster</p>
            <ul class="gnb-menu">
                <li><a href="#">메뉴</a></li>
                <li><a href="#">소개</a></li>
                <li><a href="#">문의</a></li>
            </ul>
        </div>
    </header>
    <main>
        <section class="section1">
            <div class="hero">
                <h1 class="hero-Title">커피 한 잔의 여유</h1>
                <p class="hero-description">
                    바쁜 도시의 흐름 속에서<br>
                    일상이 잠시 휴가처럼 느껴지는 순간,<br>
                    도심 속 작은 쉼표를 전합니다.
                </p>
                <button class="menu-button">메뉴보기</button>
            </div>
            <img src="Images/11.avif" alt="">
        </section>
        <section class="section2">
            <div class="menu-Group1">
                <h2>몬스터</h2>
                <ul class="menu-img1">
                    <li><img src="Images/22.avif" alt=""></li>
                    <li><img src="Images/33.avif" alt=""></li>
                    <li><img src="Images/44.avif" alt=""></li>
                </ul>
            </div>
            <div class="menu-Group2">
                <h2>인기메뉴</h2>
                <ul class="menu-img2">
                    <li><img src="Images/55.avif" alt=""></li>
                    <li><img src="Images/66.avif" alt=""></li>
                    <li><img src="Images/77.avif" alt=""></li>
                </ul>
            </div>
        </section>
    </main>
    <footer>
        <p class="footer-logo">Monster</p>
        <p class="Address">서울 마포구 연남동</p>
    </footer>
</body>
</html>
