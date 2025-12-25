<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zainab Amin | Pharm.D Student</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&family=Open+Sans:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        :root {
            --dark-blue: #1a365d;
            --medium-blue: #2d4a7c;
            --light-blue: #4a6fa5;
            --beige: #f5f2eb;
            --light-beige: #faf9f7;
            --dark-beige: #e8e4db;
            --text-dark: #2d3748;
            --text-light: #f8f8f8;
            --accent: #4299e1;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        html {
            scroll-behavior: smooth;
        }
        
        body {
            background-color: var(--light-beige);
            color: var(--text-dark);
            line-height: 1.6;
            font-family: 'Open Sans', sans-serif;
            overflow-x: hidden;
        }
        
        h1, h2, h3, h4 {
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
            color: var(--dark-blue);
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(135deg, var(--dark-blue) 0%, var(--medium-blue) 100%);
            color: var(--text-light);
            padding: 100px 0 80px;
            text-align: center;
            position: relative;
            overflow: hidden;
            min-height: 100vh;
            display: flex;
            align-items: center;
        }
        
        header::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: url("data:image/svg+xml,%3Csvg width='100' height='100' viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M11 18c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm48 25c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm-43-7c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zm63 31c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zM34 90c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zm56-76c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zM12 86c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm28-65c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm23-11c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zm-6 60c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm29 22c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zM32 63c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zm57-13c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zm-9-21c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2zM60 91c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2zM35 41c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2zM12 60c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2z' fill='%234a6fa5' fill-opacity='0.1' fill-rule='evenodd'/%3E%3C/svg%3E");
            opacity: 0.2;
        }
        
        .floating-elements {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            overflow: hidden;
            z-index: 0;
        }
        
        .floating-element {
            position: absolute;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            animation: float 15s infinite ease-in-out;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(180deg); }
        }
        
        .header-content {
            position: relative;
            z-index: 1;
            width: 100%;
        }
        
        .profile-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 30px;
        }
        
        .profile-img {
            width: 160px;
            height: 160px;
            border-radius: 50%;
            border: 5px solid var(--beige);
            margin: 0 auto 25px;
            background-color: var(--light-beige);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--dark-blue);
            font-size: 70px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
            transition: transform 0.5s ease;
        }
        
        .profile-img:hover {
            transform: scale(1.05) rotate(5deg);
        }
        
        h1 {
            font-size: 3.2rem;
            margin-bottom: 10px;
            font-weight: 700;
            letter-spacing: 1px;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
            animation: fadeInUp 1s ease;
        }
        
        .tagline {
            font-size: 1.4rem;
            margin-bottom: 10px;
            font-weight: 400;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
            animation: fadeInUp 1s ease 0.2s both;
        }
        
        .intro-text {
            font-size: 1.1rem;
            max-width: 800px;
            margin: 20px auto 30px;
            font-weight: 300;
            line-height: 1.7;
            animation: fadeInUp 1s ease 0.4s both;
        }
        
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        .btn {
            display: inline-block;
            padding: 12px 30px;
            background-color: var(--beige);
            color: var(--dark-blue);
            text-decoration: none;
            border-radius: 30px;
            font-weight: 600;
            transition: all 0.3s ease;
            margin: 5px;
            border: 2px solid transparent;
            font-family: 'Montserrat', sans-serif;
            animation: fadeInUp 1s ease 0.6s both;
            position: relative;
            overflow: hidden;
        }
        
        .btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            transition: 0.5s;
        }
        
        .btn:hover::before {
            left: 100%;
        }
        
        .btn:hover {
            background-color: transparent;
            border-color: var(--beige);
            color: var(--beige);
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .btn-primary {
            background-color: var(--accent);
            color: white;
        }
        
        .btn-primary:hover {
            background-color: transparent;
            border-color: var(--accent);
            color: var(--accent);
        }
        
        /* Navigation */
        .navbar {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            background-color: rgba(26, 54, 93, 0.9);
            backdrop-filter: blur(10px);
            z-index: 1000;
            transition: all 0.3s ease;
        }
        
        .navbar.scrolled {
            padding: 10px 0;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1);
        }
        
        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 20px;
        }
        
        .logo {
            color: white;
            font-size: 1.5rem;
            font-weight: 700;
            text-decoration: none;
        }
        
        .nav-links {
            display: flex;
            list-style: none;
        }
        
        .nav-links li {
            margin-left: 30px;
        }
        
        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
            position: relative;
        }
        
        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background-color: var(--accent);
            transition: width 0.3s ease;
        }
        
        .nav-links a:hover::after {
            width: 100%;
        }
        
        .nav-links a:hover {
            color: var(--accent);
        }
        
        /* Section Styles */
        section {
            padding: 80px 0;
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s ease;
        }
        
        section.visible {
            opacity: 1;
            transform: translateY(0);
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
            color: var(--dark-blue);
            position: relative;
            font-size: 2.2rem;
        }
        
        .section-title::after {
            content: "";
            display: block;
            width: 80px;
            height: 4px;
            background-color: var(--light-blue);
            margin: 15px auto;
        }
        
        .section-light {
            background-color: var(--light-beige);
        }
        
        .section-medium {
            background-color: var(--beige);
        }
        
        .section-dark {
            background-color: var(--dark-blue);
            color: var(--text-light);
        }
        
        .section-dark .section-title {
            color: var(--text-light);
        }
        
        /* About Section */
        .about-content {
            display: flex;
            align-items: center;
            gap: 50px;
        }
        
        .about-text {
            flex: 1;
        }
        
        .about-text p {
            margin-bottom: 20px;
            font-size: 1.1rem;
        }
        
        .about-image {
            flex: 1;
            background-color: var(--dark-beige);
            height: 400px;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--dark-blue);
            font-size: 100px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            transition: transform 0.5s ease;
        }
        
        .about-image:hover {
            transform: scale(1.02);
        }
        
        /* Education Section */
        .education-item, .internship-item {
            background-color: white;
            border-radius: 10px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            border-left: 5px solid var(--light-blue);
            transition: transform 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .education-item::before, .internship-item::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(74, 111, 165, 0.1), transparent);
            transition: 0.5s;
        }
        
        .education-item:hover::before, .internship-item:hover::before {
            left: 100%;
        }
        
        .education-item:hover, .internship-item:hover {
            transform: translateY(-5px);
        }
        
        .education-header, .internship-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 15px;
            align-items: center;
        }
        
        .education-title, .internship-title {
            font-size: 1.5rem;
            color: var(--dark-blue);
        }
        
        .education-date, .internship-date {
            color: var(--light-blue);
            font-weight: 600;
            background-color: var(--light-beige);
            padding: 5px 15px;
            border-radius: 20px;
        }
        
        .achievements-list {
            list-style-type: none;
        }
        
        .achievements-list li {
            margin-bottom: 10px;
            padding-left: 25px;
            position: relative;
            display: flex;
            align-items: center;
        }
        
        .achievements-list li i {
            position: absolute;
            left: 0;
            color: var(--dark-blue);
            font-size: 1.2rem;
        }
        
        /* Skills Section */
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .skill-category {
            background-color: white;
            border-radius: 10px;
            padding: 30px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease;
        }
        
        .skill-category:hover {
            transform: translateY(-5px);
        }
        
        .skill-category h3 {
            color: var(--dark-blue);
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid var(--dark-beige);
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .skill-category h3 i {
            color: var(--light-blue);
        }
        
        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .skill-tag {
            background-color: var(--dark-beige);
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            color: var(--dark-blue);
            transition: all 0.3s ease;
            cursor: pointer;
        }
        
        .skill-tag:hover {
            background-color: var(--light-blue);
            color: white;
            transform: translateY(-2px);
        }
        
        .skill-tag.highlight {
            background-color: var(--light-blue);
            color: white;
        }
        
        /* Projects Section */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 30px;
        }
        
        .project-card {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        
        .project-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }
        
        .project-image {
            height: 200px;
            background-color: var(--dark-beige);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--dark-blue);
            font-size: 50px;
            position: relative;
            overflow: hidden;
        }
        
        .project-image::after {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(to bottom, rgba(255,255,255,0) 0%, rgba(255,255,255,0.2) 100%);
        }
        
        .project-content {
            padding: 25px;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
        }
        
        .project-title {
            font-size: 1.3rem;
            color: var(--dark-blue);
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .project-title i {
            color: var(--light-blue);
        }
        
        .project-description {
            margin-bottom: 20px;
            flex-grow: 1;
        }
        
        /* Contact Section */
        .contact-info {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 25px;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            gap: 20px;
            font-size: 1.1rem;
            background-color: rgba(255, 255, 255, 0.1);
            padding: 15px 25px;
            border-radius: 10px;
            transition: all 0.3s ease;
        }
        
        .contact-item:hover {
            background-color: rgba(255, 255, 255, 0.2);
            transform: translateY(-5px);
        }
        
        .contact-icon {
            width: 60px;
            height: 60px;
            background-color: var(--light-blue);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.5rem;
        }
        
        .contact-text {
            display: flex;
            flex-direction: column;
        }
        
        .contact-text a {
            color: var(--text-light);
            text-decoration: none;
            transition: color 0.3s ease;
        }
        
        .contact-text a:hover {
            color: var(--accent);
        }
        
        /* Footer */
        footer {
            background-color: var(--dark-blue);
            color: var(--text-light);
            padding: 30px 0;
            text-align: center;
        }
        
        /* Stats Section */
        .stats-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 40px;
        }
        
        .stat-item {
            text-align: center;
            background-color: white;
            padding: 30px 20px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            flex: 1;
            min-width: 200px;
            transition: transform 0.3s ease;
        }
        
        .stat-item:hover {
            transform: translateY(-5px);
        }
        
        .stat-number {
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--light-blue);
            margin-bottom: 10px;
        }
        
        .stat-label {
            font-size: 1rem;
            color: var(--text-dark);
        }
        
        /* Back to Top Button */
        .back-to-top {
            position: fixed;
            bottom: 30px;
            right: 30px;
            width: 50px;
            height: 50px;
            background-color: var(--light-blue);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s ease;
            z-index: 999;
        }
        
        .back-to-top.visible {
            opacity: 1;
            visibility: visible;
        }
        
        .back-to-top:hover {
            background-color: var(--dark-blue);
            transform: translateY(-5px);
        }
        
        /* Biomedical Informatics & Data Science Focus Section */
        .health-focus {
            background: linear-gradient(135deg, var(--medium-blue) 0%, var(--light-blue) 100%);
            color: white;
            padding: 60px 0;
            text-align: center;
        }
        
        .focus-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 30px;
        }
        
        .focus-item {
            flex: 1;
            min-width: 250px;
            padding: 30px 20px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            backdrop-filter: blur(10px);
            transition: transform 0.3s ease;
        }
        
        .focus-item:hover {
            transform: translateY(-10px);
        }
        
        .focus-icon {
            font-size: 3rem;
            margin-bottom: 20px;
            color: var(--beige);
        }
        
        .focus-title {
            font-size: 1.5rem;
            margin-bottom: 15px;
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            .about-content {
                flex-direction: column;
            }
            
            h1 {
                font-size: 2.5rem;
            }
            
            .tagline {
                font-size: 1.2rem;
            }
            
            .projects-grid {
                grid-template-columns: 1fr;
            }
            
            .education-header, .internship-header {
                flex-direction: column;
                align-items: flex-start;
                gap: 10px;
            }
            
            .stats-container {
                flex-direction: column;
            }
            
            .nav-links {
                display: none;
            }
            
            .focus-container {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <a href="#" class="logo">Zainab Amin</a>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#internships">Internships</a></li>
                <li><a href="#health-focus">Biomedical Informatics</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Header Section -->
    <header>
        <div class="floating-elements" id="floatingElements"></div>
        <div class="container">
            <div class="header-content">
                <div class="profile-container">
                    <div class="profile-img">
                        <i class="fas fa-user-md"></i>
                    </div>
                    <h1>Zainab Amin</h1>
                    <p class="tagline">Pharm.D Student</p>
                    <p class="intro-text">I am a final-year Pharm.D student driven by the purpose of making the world healthier. I am passionate about biomedical informatics and data science, and leveraging AI to advance healthcare solutions.</p>
                </div>
                <a href="#projects" class="btn btn-primary">View My Projects</a>
                <a href="#contact" class="btn">Contact Me</a>
            </div>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="section-light">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>As a Pharm.D candidate with expertise in pharmacology and clinical pharmacy, I'm uniquely positioned to bridge the gap between clinical expertise and technological innovation in healthcare.</p>
                    <p>My journey in pharmacy has equipped me with deep insights into patient care, medication therapy, and healthcare systems. Combined with my technical skills in Python, R, SQL, and data analysis, I aim to develop solutions that optimize healthcare delivery and improve patient outcomes through biomedical informatics and data science.</p>
                    <p>I believe that the future of healthcare lies at the intersection of clinical knowledge and data science, and I'm committed to being at the forefront of this transformation through biomedical informatics and data science.</p>
                    <div class="stats-container">
                        <div class="stat-item">
                            <div class="stat-number">3.40</div>
                            <div class="stat-label">CGPA / 4.00</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number">40%</div>
                            <div class="stat-label">Merit Scholarship</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number">3</div>
                            <div class="stat-label">Internships</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number">2</div>
                            <div class="stat-label">Projects</div>
                        </div>
                    </div>
                </div>
                <div class="about-image">
                    <i class="fas fa-laptop-medical"></i>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="section-medium">
        <div class="container">
            <h2 class="section-title">Education & Achievements</h2>
            
            <div class="education-item">
                <div class="education-header">
                    <h3 class="education-title">Doctor of Pharmacy (Pharm.D)</h3>
                    <span class="education-date">Graduating July 2026</span>
                </div>
                <p><strong>University:</strong> UMT, Pakistan</p>
                <p><strong>CGPA:</strong> 3.40/4.00</p>
                
                <h4 style="margin-top: 20px; color: var(--dark-blue);">Achievements:</h4>
                <ul class="achievements-list">
                    <li><i class="fas fa-trophy"></i> Awarded 40% Merit Scholarship throughout the program</li>
                    <li><i class="fas fa-star"></i> Leadership Roles:
                        <ul class="achievements-list" style="margin-top: 10px; margin-left: 20px;">
                            <li><i class="fas fa-users"></i> General Secretary, Pharmacy Student Society</li>
                            <li><i class="fas fa-award"></i> Campus Director, Hult Prize Foundation</li>
                        </ul>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Internships Section -->
    <section id="internships" class="section-light">
        <div class="container">
            <h2 class="section-title">Internships & Experience</h2>
            
            <div class="internship-item">
                <div class="internship-header">
                    <h3 class="internship-title">Pharmacy Intern</h3>
                    <span class="internship-date">Evercare Hospital</span>
                </div>
                <p>Gained hands-on experience in hospital pharmacy operations, medication dispensing, patient counseling, and clinical pharmacy services. Collaborated with healthcare teams to optimize medication therapy and ensure patient safety.</p>
            </div>
            
            <div class="internship-item">
                <div class="internship-header">
                    <h3 class="internship-title">Industry Intern</h3>
                    <span class="internship-date">Coop Selection (Top 10)</span>
                </div>
                <p>Selected among top 10 candidates for this competitive internship program. Gained exposure to pharmaceutical industry operations, quality control processes, and regulatory requirements.</p>
            </div>
            
            <div class="internship-item">
                <div class="internship-header">
                    <h3 class="internship-title">Data Analyst Intern</h3>
                    <span class="internship-date">Excelerate</span>
                </div>
                <p>Applied data analysis techniques to extract insights from healthcare datasets. Developed reports and visualizations to support decision-making processes. Utilized Python and SQL for data manipulation and analysis.</p>
            </div>
        </div>
    </section>

    <!-- Biomedical Informatics & Data Science Focus Section -->
    <section id="health-focus" class="health-focus">
        <div class="container">
            <h2 class="section-title">Biomedical Informatics & Data Science Focus</h2>
            <div class="focus-container">
                <div class="focus-item">
                    <div class="focus-icon">
                        <i class="fas fa-dna"></i>
                    </div>
                    <h3 class="focus-title">Biomedical Data Analysis</h3>
                    <p>Applying data science techniques to analyze biomedical data, extract insights, and support evidence-based decision-making in healthcare.</p>
                </div>
                <div class="focus-item">
                    <div class="focus-icon">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <h3 class="focus-title">Clinical Data Science</h3>
                    <p>Bridging clinical expertise with data science to optimize healthcare delivery, predictive modeling, and clinical decision support.</p>
                </div>
                <div class="focus-item">
                    <div class="focus-icon">
                        <i class="fas fa-robot"></i>
                    </div>
                    <h3 class="focus-title">AI in Healthcare</h3>
                    <p>Leveraging artificial intelligence and machine learning to develop innovative solutions for diagnosis, treatment, and healthcare management.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="section-medium">
        <div class="container">
            <h2 class="section-title">Technical Skills</h2>
            
            <div class="skills-container">
                <div class="skill-category">
                    <h3><i class="fas fa-code"></i> Programming & Data Analysis</h3>
                    <div class="skills-list">
                        <span class="skill-tag highlight">Python</span>
                        <span class="skill-tag highlight">R</span>
                        <span class="skill-tag highlight">SQL</span>
                        <span class="skill-tag highlight">Pandas</span>
                        <span class="skill-tag">Jupyter Notebook</span>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3><i class="fas fa-database"></i> Biomedical Informatics & Data Science</h3>
                    <div class="skills-list">
                        <span class="skill-tag highlight">Data Analysis</span>
                        <span class="skill-tag highlight">Predictive Modeling</span>
                        <span class="skill-tag">Statistical Analysis</span>
                        <span class="skill-tag">Data Visualization</span>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3><i class="fas fa-tools"></i> Tools & Technologies</h3>
                    <div class="skills-list">
                        <span class="skill-tag">Git</span>
                        <span class="skill-tag">GitHub</span>
                        <span class="skill-tag">RStudio</span>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3><i class="fas fa-pills"></i> Pharmacy Expertise</h3>
                    <div class="skills-list">
                        <span class="skill-tag">Pharmacology</span>
                        <span class="skill-tag">Clinical Pharmacy</span>
                        <span class="skill-tag">Biostatistics</span>
                        <span class="skill-tag">Patient Counseling</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="section-light">
        <div class="container">
            <h2 class="section-title">Projects</h2>
            
            <div class="projects-grid">
                <!-- Project 1 -->
                <div class="project-card">
                    <div class="project-image">
                        <i class="fas fa-pills"></i>
                    </div>
                    <div class="project-content">
                        <h3 class="project-title"><i class="fas fa-file-medical"></i> Salbutamol Drug Profile</h3>
                        <p class="project-description">A comprehensive academic assignment summarizing the pharmacology, clinical uses, drug interactions, side effects, and patient counseling points for Salbutamol.</p>
                        <a href="https://zainabamin2026.github.io/salbutamol/#" class="btn btn-primary">View Project</a>
                    </div>
                </div>
                
                <!-- Project 2 -->
                <div class="project-card">
                    <div class="project-image">
                        <i class="fas fa-robot"></i>
                    </div>
                    <div class="project-content">
                        <h3 class="project-title"><i class="fas fa-brain"></i> PharmAist - AI Pharmacy Assistant</h3>
                        <p class="project-description">An AI-driven project designed for hospital, clinical, and retail pharmacy departments that handles patient queries on medications efficiently and integrates clinical pharmacy knowledge with data analysis.</p>
                        <p class="project-description">Demonstrates readiness for real-world biomedical informatics and data science applications with features including drug information retrieval, dosage calculations, and interaction checking.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section-dark">
        <div class="container">
            <h2 class="section-title">Contact</h2>
            
            <div class="contact-info">
                <div class="contact-item">
                    <div class="contact-icon">
                        <i class="fab fa-linkedin-in"></i>
                    </div>
                    <div class="contact-text">
                        <p><strong>LinkedIn</strong></p>
                        <a href="https://www.linkedin.com/in/zainab-amin-690407287/" target="_blank">linkedin.com/in/zainab-amin-690407287/</a>
                    </div>
                </div>
                
                <div class="contact-item">
                    <div class="contact-icon">
                        <i class="fas fa-envelope"></i>
                    </div>
                    <div class="contact-text">
                        <p><strong>Email</strong></p>
                        <a href="mailto:zainabaminnotes@gmail.com">zainabaminnotes@gmail.com</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2026 Zainab Amin | Pharm.D Student | Biomedical Informatics & Data Science Enthusiast</p>
        </div>
    </footer>

    <!-- Back to Top Button -->
    <div class="back-to-top" id="backToTop">
        <i class="fas fa-arrow-up"></i>
    </div>

    <script>
        // Create floating elements
        const floatingElements = document.getElementById('floatingElements');
        for (let i = 0; i < 15; i++) {
            const element = document.createElement('div');
            element.classList.add('floating-element');
            
            // Random size and position
            const size = Math.random() * 40 + 10;
            element.style.width = `${size}px`;
            element.style.height = `${size}px`;
            element.style.left = `${Math.random() * 100}%`;
            element.style.top = `${Math.random() * 100}%`;
            
            // Random animation delay and duration
            element.style.animationDelay = `${Math.random() * 5}s`;
            element.style.animationDuration = `${Math.random() * 10 + 10}s`;
            
            floatingElements.appendChild(element);
        }

        // Navbar scroll effect
        const navbar = document.querySelector('.navbar');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                navbar.classList.add('scrolled');
            } else {
                navbar.classList.remove('scrolled');
            }
        });

        // Section reveal animation
        const sections = document.querySelectorAll('section');
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, observerOptions);

        sections.forEach(section => {
            observer.observe(section);
        });

        // Back to top button
        const backToTopButton = document.getElementById('backToTop');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 300) {
                backToTopButton.classList.add('visible');
            } else {
                backToTopButton.classList.remove('visible');
            }
        });

        backToTopButton.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });

        // Skill tags animation
        const skillTags = document.querySelectorAll('.skill-tag');
        skillTags.forEach(tag => {
            tag.addEventListener('mouseenter', () => {
                tag.style.transform = 'translateY(-5px) scale(1.05)';
            });
            
            tag.addEventListener('mouseleave', () => {
                tag.style.transform = 'translateY(0) scale(1)';
            });
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });

        // Add typing effect to the tagline
        const tagline = document.querySelector('.tagline');
        const originalText = tagline.textContent;
        tagline.textContent = '';
        
        let i = 0;
        function typeWriter() {
            if (i < originalText.length) {
                tagline.textContent += originalText.charAt(i);
                i++;
                setTimeout(typeWriter, 50);
            }
        }
        
        // Start typing effect after a short delay
        setTimeout(typeWriter, 1000);
    </script>
</body>
</html>
