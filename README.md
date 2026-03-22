<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>個人履歷 - 亞洲大學</title>
    <style>
        :root {
            --sidebar-bg: #f0f4f8;
            --accent-color: #3498db;
            --pink-accent: #fce4ec;
            --text-main: #2c3e50;
            --text-light: #546e7a;
        }

        body {
            font-family: 'PingFang TC', 'Microsoft JhengHei', sans-serif;
            background-color: #ffffff;
            color: var(--text-main);
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
        }

        .resume-wrapper {
            max-width: 900px;
            width: 100%;
            display: grid;
            grid-template-columns: 300px 1fr;
            box-shadow: 0 0 20px rgba(0,0,0,0.05);
            border-radius: 10px;
            overflow: hidden;
        }

        /* 左側側邊欄 */
        .sidebar {
            background-color: var(--sidebar-bg);
            padding: 40px 30px;
        }

        .profile-pic-container {
            width: 150px;
            height: 150px;
            margin: 0 auto 30px;
            border-radius: 50%;
            overflow: hidden;
            border: 5px solid white;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        .profile-pic {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .sidebar h2 {
            font-size: 1.2em;
            color: var(--accent-color);
            margin-bottom: 15px;
            border-bottom: 2px solid #d1d9e6;
            padding-bottom: 5px;
        }

        .contact-item {
            margin-bottom: 15px;
            font-size: 0.9em;
            word-break: break-all;
        }

        /* 技能進度條 */
        .skill-item {
            margin-bottom: 15px;
        }
        .skill-name { font-size: 0.85em; margin-bottom: 5px; display: block; }
        .progress-bar {
            height: 8px;
            background: #d1d9e6;
            border-radius: 4px;
            position: relative;
        }
        .progress-fill {
            height: 100%;
            background: var(--accent-color);
            border-radius: 4px;
        }

        /* 右側主內容區 */
        .main-content {
            background: white;
            padding: 40px;
        }

        .header-title {
            margin-bottom: 40px;
        }
        .header-title h1 {
            font-size: 2.5em;
            margin: 0;
            letter-spacing: 5px;
            color: var(--accent-color);
        }
