# Just One More?

## Observed phenomenon

This project explores one possible pattern of infinite scrolling. People may continue looking at new social-media content even when they originally intended to stop. It does not claim that every person uses social media in the same way.

## How the model works

The user selects an original purpose for opening an app and a planned amount of time. The model then shows content cards with different simplified features, such as a post from a friend, novelty, a topic match, or a trending headline. Each card is labeled as either matching or differing from the original purpose. The user can continue or stop at any moment.

After repeated scrolling, the model asks the user why they continued. The final screen compares the original purpose and planned time with the model path, including content matches, different content, and the user's selected reasons. The "Pull" number is a made-up value for this model, not a measurement of real motivation.

## Run it

Open `index.html` in a web browser. No installation is required.

## Computational thinking

- **Decomposition:** original purpose, planned time, content properties, continuing or stopping, and user-reported reasons.
- **Pattern recognition:** each new post can create another opportunity to continue.
- **Abstraction:** the model represents only a few variables and leaves out emotions, habits, relationships, accessibility needs, and real platform algorithms.
- **Algorithm:** choose purpose and planned time, show content, let the user continue or stop, update model state, and compare the final path with the original plan.

## AI use and reflection

AI helped turn an observation into a browser-based prototype and suggested ways to simplify the behavior into code. I decided which states to represent, how content could match or differ from a purpose, and how to make the user's own choices visible. I revised an earlier version because the original purpose only appeared in the final summary. In this version, the purpose affects whether content is labeled as matching or different and changes the model's Pull value.
