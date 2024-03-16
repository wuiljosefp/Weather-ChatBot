# CityWeatherBot

## Problem Statement

People often search for activities to engage in within their city, but their choices may be influenced by weather conditions. Presently, there's no centralized platform providing real-time, personalized suggestions based on local weather, especially through messaging platforms like Telegram.

## Solution

We propose developing an intelligent Chatbot on Telegram that leverages weather forecasting services and other relevant sources to offer activity suggestions tailored to current weather conditions. This Chatbot will provide a friendly and efficient interaction experience within the Telegram environment.

## System Flow

1. **User Interaction**:
   - Users initiate a conversation with the Chatbot on Telegram and provide their city's location.

2. **Weather Retrieval**:
   - The Chatbot utilizes Azure's weather forecasting service to retrieve updated weather information.

3. **Activity Suggestions**:
   - Based on the weather, the Chatbot suggests relevant activities, presenting options clearly and concisely.

4. **User Engagement**:
   - Users can request additional details about specific activities, adjust preferences, or ask for new suggestions.

5. **Additional Information**:
   - The Chatbot can also provide details about local events, points of interest, and popular activities using Azure Cognitive Services data.

## Features

- **Weather Retrieval**:
  - Integrate Azure Weather API to obtain real-time weather forecast data.

- **Activity Suggestions**:
  - Utilize intelligent algorithms based on Azure AI to generate activity suggestions considering both weather conditions and user preferences.

- **Natural Interaction**:
  - Implement Azure Cognitive Services (NLP) for more natural interaction and better understanding of user language.

- **Local Events Integration**:
  - Utilize Azure's local event data to provide updated information on nearby activities and events.

- **Personalization**:
  - Enable users to set preferences and receive personalized suggestions, storing this information in an Azure database.

## Technologies Used

- **Azure Bot Service**:
  - Develop and host the Chatbot on Azure Bot Service for seamless integration with Telegram.

- **Azure Cognitive Services (NLP)**:
  - Integrate Azure's natural language processing services to enhance the Chatbot's understanding and responses.

- **Azure Weather API**:
  - Utilize this service to obtain accurate and up-to-date weather data.

- **Azure Database**:
  - Store user preferences and relevant data to enhance the customization of suggestions.

- **Telegram Bot API**:
  - Integrate the Telegram API to manage user interactions on the platform.

- **Development Platforms**:
  - Utilize technologies such as Node.js, Python, or C# based on the team's preferences and skills, ensuring compatibility with Azure infrastructure.

## Setup Instructions

1. Clone the repository.
2. Set up Azure services and APIs as described in the documentation.
3. Configure the Chatbot according to your requirements.
4. Deploy the Chatbot on Azure Bot Service.
5. Integrate with Telegram Bot API.
6. Start engaging users with personalized activity suggestions!

## Contributors

- [Valentina Lazaro](https://github.com/ValexLaz)
- [Leonardo Olaechea](https://github.com/Dreamlocked)
- [Wuilson Flores](https://github.com/wuiljosefp)
