# XENON-
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>XENON - Vendas de Camisetas, Roupas e Acessórios</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #2b79a0;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #1d4e74;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 16px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin: 20px;
        }

        .product {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 300px;
            margin: 15px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .product img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }

        .product h3 {
            color: #2b79a0;
            font-size: 20px;
            margin: 10px 0;
        }

        .product p {
            color: #666;
            font-size: 14px;
            margin-bottom: 10px;
        }

        .product .price {
            font-size: 18px;
            color: #1d4e74;
            margin-top: 10px;
        }

        footer {
            background-color: #2b79a0;
            color: white;
            text-align: center;
            padding: 20px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>XENON</h1>
        <p>Bem-vindo à nossa loja de camisetas, roupas e acessórios!</p>
    </header>

    <nav>
        <a href="#home">Início</a>
        <a href="#produtos">Produtos</a>
        <a href="#contato">Contato</a>
        <a href="#sobre">Sobre</a>
    </nav>

    <section id="home">
        <div class="container">
            <div class="product">
                <img src="https://via.placeholder.com/300x200" alt="Camiseta Estilosa">
                <h3>Camiseta Estilosa</h3>
                <p>Camiseta de algodão com estampa criativa, ideal para o seu estilo.</p>
                <p class="price">R$ 59,90</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200" alt="Jaqueta Moderna">
                <h3>Jaqueta Moderna</h3>
                <p>Jaqueta com design único para o inverno, confortável e estilosa.</p>
                <p class="price">R$ 149,90</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200" alt="Boné Casual">
                <h3>Boné Casual</h3>
                <p>Boné casual de alta qualidade para completar seu look diário.</p>
                <p class="price">R$ 39,90</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 XENON. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
