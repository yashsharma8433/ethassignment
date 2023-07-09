
# ethassignment

This Solidity program is of creating of token

## code requirements

1. Contract have public variables that store the details about the coin (Token Name, Token Abbrv., Total Supply).
   
3. Contract will have a mapping of addresses to balances (address => uint).
   
4. It will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the address by that amount.

4.Contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.

5.Burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.


## Author

yash sharma 


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
