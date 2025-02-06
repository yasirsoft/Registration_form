<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration Form</title>
</head>
<body>
    <h1>Student Information Form</h1>
    <form>
        <label for="firstName">First Name:</label><br>
        <input type="text" id="firstName" name="firstName"><br><br>

        <label for="lastName">Last Name:</label><br>
        <input type="text" id="lastName" name="lastName"><br><br>

        <label for="email">Email Address:</label><br>
        <input type="email" id="email" name="email"><br><br>

        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password"><br><br>

        <label for="confirmPassword">Confirm Password:</label><br>
        <input type="password" id="confirmPassword" name="confirmPassword"><br><br>

        <label for="phone">Phone Number:</label><br>
        <input type="tel" id="phone" name="phone"><br><br>

        <label>Gender:</label><br>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label><br>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br><br>

        <label for="division">Select your division:</label><br>
        <select id="division" name="division">
            <option value="Barisal">Barisal</option>
            <option value="Chittagong">Chittagong</option>
            <option value="Dhaka">Dhaka</option>
            <option value="Khulna">Khulna</option>
            <option value="Rajshahi">Rajshahi</option>
            <option value="Rangpur">Rangpur</option>
            <option value="Sylhet">Sylhet</option>
        </select><br><br>

        <label for="image">Choose your image:</label><br>
        <input type="file" id="image" name="image"><br><br>

        <label for="birthdate">Select your birth date:</label><br>
        <input type="date" id="birthdate" name="birthdate"><br><br>

        <label for="time">Select just time:</label><br>
        <input type="time" id="time" name="time"><br><br>

        <label for="color">Color pick:</label><br>
        <input type="color" id="color" name="color"><br><br>

        <label for="url">Please enter a URL:</label><br>
        <input type="url" id="url" name="url"><br><br>

        <label for="details">Text details:</label><br>
        <textarea id="details" name="details"></textarea><br><br>

        <input type="reset" value="Reset Form">
        <input type="submit" value="Submit">
    </form>
</body>
</html>
