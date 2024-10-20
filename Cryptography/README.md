### Challenge 1: Drink Up

- **Description:** The challenge involved analyzing a can with the company name **XXTEA**. The steps to retrieve the flag included base64 decoding followed by XXTEA decryption. The key used for decryption was **"Tea Turned Up to the Max!"**. The flag was extracted from the decrypted text.
- **Steps:**

![image](https://github.com/x03ee/DeadFaceCTF-2024/blob/main/Cryptography/Drink%20Up/drink.png)

  1. **Base64 Decode** the provided string.
  2. **XXTEA Decrypt** the resulting text using the key.
- **Encoded Text:**
  ```
  zxk1ehfZ/kx7tzSyQeSm2XuGitnxsN8rG/mwxNaCjFFc2rCrTTWpwViZFpwI4xRccvdwm/Ta6l3GFeaPs96l7BPziIu+DsfoS6bdy5ByHSyW+D5bCgtTCuoVvMOlPC7xILtjlt6/Ky6ZPaV40gfmtM/iuRGR+zveFLNyWy9Tlu3TnOaq0lP6wp65lGEFBTHPSwho0jIP47pxoKryxnh7svJrTD1wh+D+YudNjDpPr39yH/iMlU+5xiK2dXjiD0UtL3vSSQ55MLCPpN/kFW6AuO2OEuadKXg2XYiXnAkLJcUxGdZhP7+Lo4LG3m5HsHdBmul5pX9gcvERFQSZOy2QfEv3+vRfLfoJPq6WQnBjwXUoVo/YHeD8SS+TDvg=
  ```

![image1](https://github.com/x03ee/DeadFaceCTF-2024/blob/main/Cryptography/Drink%20Up/solution.png)

- **Flag:** `flag{br3wed_4_the_B0ld!}`

---

### Challenge 2: Ides-le Talk

- **Description:** This challenge required a simple **ROT13** decoding of the text to obtain the flag. ROT13 is a letter substitution cipher that replaces a letter with the 13th letter after it in the alphabet.

![image2](https://github.com/x03ee/DeadFaceCTF-2024/blob/main/Cryptography/Ides-le%20Talk/flag.png)

- **Flag:** `flag{L3t The#Mischiefs^8361n}`

---

### Challenge 3: Social Pressure

- **Description:** The objective of this challenge was to decode a message using the **Atbash** cipher, which substitutes letters in a mirrored alphabet. After decoding, the name was extracted and formatted within the flag.

![image3](https://github.com/x03ee/DeadFaceCTF-2024/blob/main/Cryptography/Social%20Pressure/flag.png)

- **Flag:** `flag{Elroy Ongaro}`
