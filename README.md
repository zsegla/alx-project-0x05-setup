# Submit vs Click Event in JavaScript

This mini-project demonstrates the difference between the `submit` event and the `click` event in JavaScript using a simple HTML form.

## 🔍 Overview

- The `click` event occurs when a user directly clicks a button or element.
- The `submit` event is triggered when a form is submitted, either by:
  - Clicking a submit button, or
  - Pressing "Enter" inside a form input field.

## 🧪 Key Observations

| User Action                   | Triggers `click` | Triggers `submit` |
|------------------------------|------------------|-------------------|
| Clicking the button          | ✅ Yes            | ✅ Yes             |
| Pressing Enter in input      | ❌ No             | ✅ Yes             |

## 💻 Code Example

```html
<form id="myForm">
  <label for="name">Name:</label>
  <input type="text" id="name" />
  <button type="submit" id="submitBtn">Submit</button>
</form>
