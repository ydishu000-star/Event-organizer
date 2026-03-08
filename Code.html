<!DOCTYPE html>
<html>
<head>
    <title>Smart Event Dashboard</title>

    <style>
        /* ====== BODY STYLE (BOLD COLORS) ====== */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: linear-gradient(
                270deg,
                #ff0000,   /* Bright Red */
                #ff00ff,   /* Neon Pink */
                #00ffff,   /* Cyan */
                #00ff00,   /* Lime Green */
                #ffff00    /* Yellow */
            );
            background-size: 800% 800%;
            animation: gradientMove 8s ease infinite;
            padding: 20px;
        }

        @keyframes gradientMove {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        h1 {
            text-align: center;
            color: white;
            font-size: 32px;
            text-shadow: 2px 2px 5px black;
        }

        .container {
            display: flex;
            gap: 20px;
            margin-top: 20px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 15px;
            width: 50%;
            box-shadow: 0 6px 15px rgba(0,0,0,0.4);
        }

        .card h2 {
            color: #ff00ff;
            font-weight: bold;
        }

        input, select, textarea {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border-radius: 8px;
            border: 2px solid #00ffff;
        }

        button {
            padding: 10px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            margin-top: 5px;
            font-weight: bold;
            transition: 0.3s;
        }

        button:hover {
            transform: scale(1.05);
        }

        .add-btn {
            background: #00ff00;
            color: black;
        }

        .clear-btn {
            background: #ff0000;
            color: white;
        }

        .sample-btn {
            background: #ffff00;
            color: black;
        }

        .event {
            background: #f8f8f8;
            padding: 12px;
            border-left: 6px solid #ff00ff;
            margin-top: 10px;
            border-radius: 8px;
        }

        .delete-btn {
            background: black;
            color: white;
            float: right;
        }

        .dom-box {
            margin-top: 30px;
            background: white;
            padding: 20px;
            border-radius: 15px;
        }
    </style>
</head>

<body>

<h1>🎯 Smart Event Dashboard</h1>

<div class="container">

    <div class="card">
        <h2>Add New Event</h2>

        <input type="text" id="title" placeholder="Event Title">
        <input type="date" id="date">

        <select id="category">
            <option>Conference</option>
            <option>Workshop</option>
            <option>Meeting</option>
            <option>Birthday</option>
        </select>

        <textarea id="description" placeholder="Description"></textarea>

        <button class="add-btn" onclick="addEvent()">Add Event</button>
    </div>

    <div class="card">
        <h2>My Events</h2>

        <button class="clear-btn" onclick="clearEvents()">Clear All</button>
        <button class="sample-btn" onclick="addSample()">Add Sample</button>

        <div id="eventList"></div>
    </div>

</div>

<div class="dom-box">
    <h2>DOM Manipulation Demo</h2>
    <p id="keyDisplay">Press any key...</p>
</div>

<script>
    function addEvent() {

        let title = document.getElementById("title").value;
        let date = document.getElementById("date").value;
        let category = document.getElementById("category").value;
        let description = document.getElementById("description").value;

        if (title === "" || date === "") {
            alert("Please enter title and date!");
            return;
        }

        let eventDiv = document.createElement("div");
        eventDiv.className = "event";

        eventDiv.innerHTML = `
            <strong>${title}</strong> (${category})<br>
            Date: ${date}<br>
            ${description}
            <button class="delete-btn" onclick="this.parentElement.remove()">X</button>
        `;

        document.getElementById("eventList").appendChild(eventDiv);

        document.getElementById("title").value = "";
        document.getElementById("date").value = "";
        document.getElementById("description").value = "";
    }

    function clearEvents() {
        document.getElementById("eventList").innerHTML = "";
    }

    function addSample() {
        document.getElementById("title").value = "Music Festival";
        document.getElementById("date").value = "2026-04-15";
        document.getElementById("category").value = "Meeting";
        document.getElementById("description").value = "Live DJ and fun activities";
        addEvent();
    }

    document.addEventListener("keydown", function(event) {
        document.getElementById("keyDisplay").innerText =
            "You Pressed: " + event.key;
    });
</script>

</body>
</html>
