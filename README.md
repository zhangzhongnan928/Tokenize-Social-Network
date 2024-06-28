# Tokenize Social Network
Experiment on Tokenizing Social Network

If Web3 is about ownership, then in social networks, what you can truly own are the rights other users and/or the platform grant/provide/promise to you. All these rights form the relationships (the network) between you and others. The carrier of these rights in Web3 should be tokens, specifically interactive tokens. Anything else can be built on top of these tokens.

## Core Concept

In a tokenized social network, each right is represented by an interactive token. These tokens are the fundamental building blocks of the social graph, allowing for granular control, transparency, and portability of social interactions.

## Key Points

### 1. Rights as Tokens
- Each social network right is embodied in an interactive token
- Tokens form the basis of the social graph

### 2. Relationship Formation
- Exchange and possession of right tokens create and define relationships

### 3. Interactive Tokens
- Tokens are not static; they contain executable functions
- Functions related to the right can be used directly on the token
- No need to open a specific website/app to use the token's functions
- Fully portable across different platforms and environments

### 4. Granular Control
- Precise management of social interactions through token control

### 5. Interoperability
- Tokens and their functions usable across various platforms

## Example Types of Right Tokens and Their Functions
(some rights can be carried by one token, or one token can spplit into mutiple tokens)

1. **View Token**
   - Function: `viewContent(contentId)`
   - Grants right to view specific content
   - Can be executed directly from a wallet or any compatible interface

2. **Interact Token**
   - Functions: `comment(contentId, text)`, `like(contentId)`, `share(contentId)`
   - Allows interaction with content
   - Executable anywhere the token is recognized

3. **Connect Token**
   - Function: `sendMessage(userId, message)`
   - Enables direct communication
   - Can be used in any messaging interface that recognizes the token

4. **Create Token**
   - Function: `createContent(contentType, data)`
   - Gives right to create content in specific contexts
   - Content creation possible wherever the token is accepted

5. **Moderate Token**
   - Functions: `removeContent(contentId)`, `flagUser(userId)`
   - Grants moderation powers
   - Moderation actions can be performed from any compatible interface

6. **Privacy Token**
   - Function: `setVisibility(dataType, level)`
   - Controls visibility of user's information
   - Privacy settings adjustable from any platform recognizing the token

7. **Data Access Token**
   - Function: `grantAccess(dataType, recipientId, duration)`
   - Manages who can access and use user's data
   - Data permissions manageable across different services

## Potential Implementations

### 1. Friend Relationship
- User A gives User B: View Token, Interact Token, Connect Token
- User B reciprocates with the same tokens

### 2. Follow Relationship
- User A gives User B: View Token (for public posts)
- No reciprocation needed from User B

### 3. Group Membership
- Group admin gives members: Group Interact Token
- Members receive: Group View Token for exclusive content

### 4. Content Creator-Subscriber
- Creator gives subscribers: Exclusive View Token
- Subscribers receive: Priority Interact Token

## Advantages

1. **Transparency**: Clear definition of relationships and permissions through token ownership
2. **Flexibility**: Easy granting, revoking, or modification of rights via token transfer
3. **User Empowerment**: Full control over social graph and data
4. **Innovation**: New social interactions possible by combining different tokens
5. **Monetization**: Potential for trading or leasing rights tokens
6. **Portability**: Token functions usable across various platforms without dependence on specific apps

## Challenges to Consider

1. **Complexity**: Potential user overwhelm in managing multiple tokens
2. **Privacy**: Ensuring token transactions don't reveal sensitive information
3. **Scalability**: Efficient handling of billions of tokens and their interactions
4. **User Experience**: Creating intuitive interfaces for token management and function execution
5. **Regulatory Compliance**: Navigating data protection laws and regulations
6. **Standardization**: Developing common standards for token functions across platforms




| User A grants | User B grants | User C grants | Resulting Relationship |
|---------------|---------------|---------------|------------------------|
| To B:<br>• View friends-only posts<br>• Comment on all posts<br>• Send direct messages<br>• View friend list<br>• View full profile<br>• Tag in posts/photos<br><br>To C:<br>• View public posts<br>• Comment on public posts<br>• Share public posts | To A:<br>• View friends-only posts<br>• Comment on all posts<br>• Send direct messages<br>• View friend list<br>• View full profile<br>• Tag in posts/photos<br><br>To C:<br>• View public posts<br>• Comment on public posts<br>• Share public posts | To A:<br>• View public posts<br>• Comment on public posts<br>• Share public posts<br><br>To B:<br>• View public posts<br>• Comment on public posts<br>• Share public posts | A and B are Mutual Friends<br><br>A and C are Mutual Followers<br><br>B and C are Mutual Followers |
| To B:<br>• View public posts<br>• Comment on public posts<br>• Share public posts<br><br>To C:<br>• None | To A:<br>• None<br><br>To C:<br>• View public posts<br>• Comment on public posts<br>• Share public posts | To A:<br>• View public posts<br>• Comment on public posts<br>• Share public posts<br><br>To B:<br>• View public posts<br>• Comment on public posts<br>• Share public posts | A follows B<br><br>B follows C<br><br>C follows A |
| To B:<br>• None<br><br>To C:<br>• View public posts<br>• Comment on public posts<br>• Share public posts | To A:<br>• View public posts<br>• Comment on public posts<br>• Share public posts<br><br>To C:<br>• None | To A:<br>• View public posts<br>• Comment on public posts<br>• Share public posts<br><br>To B:<br>• View public posts<br>• Comment on public posts<br>• Share public posts | A and B are Mutual Followers<br><br>A and C are Mutual Followers<br><br>B follows C |
| To B:<br>• None<br><br>To C:<br>• View public posts<br>• Comment on public posts<br>• Share public posts | To A:<br>• None<br><br>To C:<br>• View public posts<br>• Comment on public posts<br>• Share public posts | To A:<br>• None<br><br>To B:<br>• None | A blocks B<br><br>A and C are Mutual Followers<br><br>B and C are Mutual Followers |
