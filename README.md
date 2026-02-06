<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Resume</title>
   <style>
    * {
        box-sizing: border-box;
    }

    body {
        font-family: "Segoe UI", Tahoma, Arial, sans-serif;
        background: linear-gradient(135deg, #e3f2fd, #f9f9f9);
        margin: 0;
        padding: 40px 0;
        color: #333;
    }

    .resume {
        max-width: 850px;
        background: #ffffff;
        margin: auto;
        padding: 40px;
        border-radius: 12px;
        box-shadow: 0 15px 35px rgba(0,0,0,0.12);
    }

    .header {
        display: flex;
        align-items: center;
        gap: 25px;
        border-bottom: 3px solid #2196f3;
        padding-bottom: 25px;
        margin-bottom: 30px;
    }

    .header img {
        width: 140px;
        height: 140px;
        border-radius: 50%;
        object-fit: cover;
        border: 4px solid #2196f3;
    }

    h1 {
        margin: 0;
        font-size: 34px;
        color: #1a237e;
    }

    .info {
        font-size: 14px;
        color: #555;
        margin-top: 8px;
        line-height: 1.6;
    }

    .section {
        margin-bottom: 30px;
    }

    .section h2 {
        font-size: 22px;
        color: #2196f3;
        margin-bottom: 12px;
        padding-bottom: 6px;
        border-bottom: 2px solid #e0e0e0;
        letter-spacing: 0.5px;
    }

    p {
        margin: 8px 0;
        line-height: 1.6;
    }

    ul {
        padding-left: 22px;
        margin-top: 10px;
    }

    ul li {
        margin-bottom: 8px;
        line-height: 1.5;
    }

    strong {
        color: #000;
    }

    /* Skills layout improvement */
    .section ul {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    }

    /* Small screens */
    @media (max-width: 600px) {
        .header {
            flex-direction: column;
            text-align: center;
        }

        .header img {
            margin-bottom: 15px;
        }
    }
</style>

</head>
<body>

<div class="resume">
    <div class="header">
        <!-- YOUR PHOTO -->
        <img src="arf.jpg" alt="Profile Picture">

        <div>
            <h1>Jack Daniel Robles</h1>
            <div class="info">
                Email: jack@gmail.com<br>
                Phone: 09123545676<br>
                Location: Philippines
            </div>
        </div>
    </div>

    <div class="section">
        <h2>Professional Summary</h2>
        <p>
            A dedicated and enthusiastic learner with foundational knowledge and hands-on
           experience gained through academic projects and training. Eager to
            apply skills in a real-world environment, grow professionally,
           and contribute positively to an organization.
        </p>
    </div>

    <div class="section">
        <h2>Skills</h2>
        <ul>
            <li> debugging</li>
            <li> code</li>
            <li>Skill ewann ko</li>
        </ul>
    </div>

    <div class="section">
        <h2>Work Experience</h2>
        <p><strong>Job Title</strong> – LGU Paombong</p>
        <p>2025 – 2026</p>
        <ul>
            <li>Assisted in system maintenance, data managemen and user support</li>
            <li>Improved filing and record-keeping processes for better efficiency</li>
        </ul>
    </div>

    <div class="section">
        <h2>Education</h2>
        <p><strong>Degree</strong> – Bulacan Polythecnic college </p>
        <p>2026</p>
    </div>
</div>

</body>
</html>
