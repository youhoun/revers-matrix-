<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Matrix Inverse Calculator</title>

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-gradient-to-br from-blue-600 via-cyan-500 to-indigo-700 min-h-screen">

<div class="container mx-auto py-10 px-4">

    <div class="max-w-7xl mx-auto bg-white rounded-2xl shadow-2xl p-8">

        <h1 class="text-4xl font-bold text-center text-blue-700 mb-2">
            🧮 Matrix Inverse Calculator
        </h1>

        <p class="text-center text-gray-500 mb-8">
            Gauss-Jordan Elimination Method
        </p>

        <!-- Controls -->
        <div class="flex flex-wrap justify-center items-center gap-4">

            <label class="font-semibold text-lg">
                Matrix Size (N × N)
            </label>

            <input
                id="size"
                type="number"
                min="2"
                max="20"
                value="2"
                class="w-24 px-3 py-2 text-center border-2 border-blue-500 rounded-lg focus:ring-4 focus:ring-blue-300 focus:outline-none">

            <button
                onclick="createMatrix()"
                class="bg-blue-600 hover:bg-blue-700 text-white px-5 py-2 rounded-lg shadow transition duration-300">
                Create Matrix
            </button>

            <button
                onclick="inverseMatrix()"
                class="bg-green-600 hover:bg-green-700 text-white px-5 py-2 rounded-lg shadow transition duration-300">
                Calculate
            </button>

            <button
                onclick="clearMatrix()"
                class="bg-red-600 hover:bg-red-700 text-white px-5 py-2 rounded-lg shadow transition duration-300">
                Clear
            </button>

        </div>

        <!-- Matrix -->
        <div id="matrixInputs"
             class="overflow-auto mt-8 flex justify-center">
        </div>

        <!-- Result -->
        <div id="result" class="mt-10"></div>

    </div>

</div>

<script>

window.onload = createMatrix;

//----------------------------

function createMatrix(){

    let n = parseInt(document.getElementById("size").value);

    if(isNaN(n) || n < 2){

        alert("Matrix size must be at least 2.");
        return;

    }

    let html = "<table class='border-separate border-spacing-2'>";

    for(let i=0;i<n;i++){

        html += "<tr>";

        for(let j=0;j<n;j++){

            html += `
            <td>
                <input
                    type="number"
                    step="any"
                    value="0"
                    id="a${i}${j}"
                    class="w-20 h-12 text-center border border-gray-300 rounded-lg shadow-sm focus:ring-2 focus:ring-blue-400 focus:outline-none">
            </td>
            `;

        }

        html += "</tr>";

    }

    html += "</table>";

    document.getElementById("matrixInputs").innerHTML = html;
    document.getElementById("result").innerHTML = "";

}

//----------------------------

function clearMatrix(){

    let n = parseInt(document.getElementById("size").value);

    for(let i=0;i<n;i++){

        for(let j=0;j<n;j++){

            document.getElementById(`a${i}${j}`).value = 0;

        }

    }

    document.getElementById("result").innerHTML = "";

}

//----------------------------

function inverseMatrix(){

    let n = parseInt(document.getElementById("size").value);

    let a = [];

    // Read matrix
    for(let i=0;i<n;i++){

        a[i] = [];

        for(let j=0;j<n;j++){

            let value = parseFloat(document.getElementById(`a${i}${j}`).value);

            if(isNaN(value))
                value = 0;

            a[i][j] = value;

        }

    }

    // Create augmented matrix [A | I]

    for(let i=0;i<n;i++){

        for(let j=n;j<2*n;j++){

            a[i][j] = (j === i+n) ? 1 : 0;

        }

    }

    // Gauss-Jordan Elimination

    for(let i=0;i<n;i++){
