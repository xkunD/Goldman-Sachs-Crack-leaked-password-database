# Goldman-Sachs-Crack-leaked-password-database
 ## 😃 Overview
 As a governance analyst it is part of your duties to assess the level of protection offered by implemented controls and minimize the probability of a successful breach. To be successful at your job you often need to know the techniques used by hackers to circumvent implemented controls and propose uplifts to increase the overall level of security in an organization. Gaining valid credentials gives the attackers access to the organization’s IT system, thus circumventing most of perimeter controls in place.
 
 ## 📌 Project Objective
 Your job is to crack as many passwords as possible with available tools. Here are your Task instructions:

- Review the links provided in the additional resources (section 4) below to gain a background understanding of password cracking
- Try to crack the passwords provided in the 'password dump' file below using available tools
- Assess the 5 questions in the task instructions below in relation to the passwords provided (type of hashing algorithm, level of protection, possible controls that could be implemented, password policy, changes in policy)
- Draft an email/memo briefly explaining your findings in relation to controls used by the organization and your proposed uplifts.

## 🔎 Observations
Sample passwords provided are available at [passwd_dump.txt](https://cdn.theforage.com/vinternships/companyassets/MBA4MnZTNFEoJZGnk/passwd_dump.txt).

After cracking:
```
Security Algorithms used: 
experthead:e10adc3949ba59abbe56e057f20f883e – MD5
interestec:25f9e794323b453885f5181f1b624d0b – MD5
ortspoon:d8578edf8458ce06fbc5bb76a58c5ca4 –MD5
reallychel:5f4dcc3b5aa765d61d8327deb882cf99 –MD5
simmson56:96e79218965eb72c92a549dd5a330112 – MD5
bookma:25d55ad283aa400af464c76d713c07ad – MD5 
popularkiya7:e99a18c428cb38d5f260853678922e03 – MD5
eatingcake1994:fcea920f7412b5da7be0cf42b8c93759 – MD5 
heroanhart:7c6a180b36896a0a8c02787eeafb0e4c – MD5
edi_tesla89:6c569aabbf7775ef8fc570e228c16b98 – MD5
liveltekah:3f230640b78d7e71ac5514e57935eb69 – MD5
blikimore:917eb5e9d6d6bca820922a0c6f7cc28b – MD5
johnwick007:f6a0cb102c62879d397b12b62c092c06 – MD5
flamesbria2001:9b3b269ad0a208090309f091b3aba9db – MD5
oranolio:16ced47d3fc931483e24933665cded6d - MD5
spuffyffet:1f5c5683982d7c3814d4d9e6d749b21e - MD5
moodie:8d763385e0476ae208f21bc63956f748 - MD5
nabox:defebde7b6ab6f24d5824682a16c3ae4 - MD5
bandalls:bdda5f03128bcbdfa78d8934529048cf - MD5

Cracked Passwords:
experthead:e10adc3949ba59abbe56e057f20f883e - 123456
interestec:25f9e794323b453885f5181f1b624d0b - 123456789
ortspoon:d8578edf8458ce06fbc5bb76a58c5ca4 - qwerty
reallychel:5f4dcc3b5aa765d61d8327deb882cf99 - password
simmson56:96e79218965eb72c92a549dd5a330112 - 111111
bookma:25d55ad283aa400af464c76d713c07ad - 12345678
popularkiya7:e99a18c428cb38d5f260853678922e03 - abc123
eatingcake1994:fcea920f7412b5da7be0cf42b8c93759 - 1234567
heroanhart:7c6a180b36896a0a8c02787eeafb0e4c - password1
edi_tesla89:6c569aabbf7775ef8fc570e228c16b98 - password!
liveltekah:3f230640b78d7e71ac5514e57935eb69 - qazxsw
blikimore:917eb5e9d6d6bca820922a0c6f7cc28b - Pa$$word1
johnwick007:f6a0cb102c62879d397b12b62c092c06 - bluered
```
## 📄 Email Report
```
Dear Sir/Madam,

Hope you are doing well!

After trying to crack the passwords you provided, I found there're potential risks existing in the password policy of the organization, 
and I would like to be explain all my findings, conclusions as well as my suggestions to improve the password policy.

All passwords you provided are coded using Message-Digest (MD5) cryptographic hash function, which is a standard algorithm 
but comparatively weak and insecure, and could be attacked in a short time using Brute Force.

Because of that, some controls could be implemented to avoid the password database leaking again:
1.    Using a hashing algorithm which provides a high level of protection, such as SHA - 256 or SHA - 3.
2.    Introduce password salting to safeguard passwords in storage.

Also, there're something else that are damaging the security of passwords in your password policy:
1.    The minimum password length is set to be 6, which is supposed to be longer.
2.    Passwords are allowed to be any combination of letters, numbers and symbols, even pure letters/numbers are allowed.

Here're my suggestions:
1.    Set the minimum password length to be at least 8 characters.
2.    Avoid containing common words like 'password', or simple string of numbers like '11111' '123456' in passwords, 
        nor users' names and dates of birth.
3.    Recommend users to include capital letters, small letters, numbers, and special characters in their passwords.

Hope you find them helpful!

Thanks,
Xiaokun Du

```
## 📚 Resources

- Goldman Sach Virtual Internship Programme: [https://www.theforage.com/virtual-internships/prototype/NPdeQ43o8P9HJmJzg/Goldman-Sachs-Virtual-Experience-Program?ref=WXfC2wsoQxMokZAmF](https://www.theforage.com/virtual-internships/prototype/NPdeQ43o8P9HJmJzg/Goldman-Sachs-Virtual-Experience-Program?ref=WXfC2wsoQxMokZAmF)
- Password Cracking Explained: [https://arstechnica.com/information-technology/2013/05/how-crackers-make-minced-meat-out-of-your-passwords/](https://arstechnica.com/information-technology/2013/05/how-crackers-make-minced-meat-out-of-your-passwords/)
- Password Salting: [https://en.wikipedia.org/wiki/Salt_(cryptography)](https://en.wikipedia.org/wiki/Salt_(cryptography))
- Hash Functions: [https://en.wikipedia.org/wiki/Cryptographic_hash_function](https://en.wikipedia.org/wiki/Cryptographic_hash_function)
- Password Cracking Tools: [https://en.wikipedia.org/wiki/Password_cracking#Software](https://en.wikipedia.org/wiki/Password_cracking#Software)
- Password Strength Checker: [https://howsecureismypassword.net/](https://howsecureismypassword.net/)
- Password Dump: [https://cdn.theforage.com/vinternships/companyassets/MBA4MnZTNFEoJZGnk/passwd_dump.txt](https://cdn.theforage.com/vinternships/companyassets/MBA4MnZTNFEoJZGnk/passwd_dump.txt)


 
