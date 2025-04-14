# 💰 Question Details and Betting

After clicking on a question card, users will enter the question details page with the following main features:

1. **Question Tag Editing**
   - Limited to question creators, can edit up to 5 tags for future classification and retrieval.
2. **Data Charts**
   - Charts display betting data trends for each option, helping users understand current market dynamics.
3. **Time Information**
   - Clearly displays the question's start and end times.
4. **Favorite Questions**
   - Users can favorite questions of interest for quick access.
5. **Betting Operations**
   - In the betting area:
     - **Select Options**: Users can select multiple options for questions, but when a question is in "Winner Takes All" mode, only [Yes] betting is allowed.
     - **Choose Result**: Select betting result (Yes or No).
     - **Enter Betting Amount**: Betting amount unit is USDT.
     - **First Token Authorization**:
       - First-time betting requires token authorization to ensure users agree to the platform using their USDT funds for betting, preventing unauthorized transactions.
     - **Confirm Betting**: After clicking the [Vote] button, the system will prompt the wallet for transaction confirmation, and the page will automatically refresh to show the latest betting data.
6. **Share Holdings Display**
   - Shows the shares and expected returns users currently hold after betting.
7. **Rules Display**
   - Displays the detailed description filled during question creation, helping users understand the question background and verification rules.
8. **Resolution Operations Area**
   - When an option or the entire question has a resolution answer, the question creator can enter the proposal process:
     - **Submit Proposal**
       - Proposals can only be submitted after the voting end time, ensuring all betting activities are completed.
       - After proposal submission, the question enters a 12-hour challenge period.
       - **Challenge Period Explanation**:
         - During the 12-hour challenge period, if no objections are raised, the system automatically confirms the answer; proposers receive 2% of the losing side's rewards.
         - New proposals cannot be submitted during the challenge period, even if different results appear for other options, must wait until the challenge period ends.
     - **Initiate Challenge**
       - During the challenge period, any user can initiate a [Challenge] operation to object to the proposed answer.
       - Initiating a challenge requires staking 500 USDT and submitting their own answer.
     - **Dispute Period Handling**
       - Once a challenge is initiated, the question enters the dispute period, and the platform automatically pushes dispute information to the Telegram community channel.
       - The final answer is determined by community voting and comprehensive advisory team opinions:
         - If the proposer wins, they receive 2% of the losing side's rewards plus the challenger's staked 500 USDT;
         - If the challenger wins, they get back their stake plus rewards;
         - If both parties are incorrect, the bonus goes to the platform.
9. **Discussion and Activity Records**
   - The question details page provides a discussion area where users can discuss and exchange views on the question.
   - Also displays top users holding shares and the question's betting activity records for historical context.
