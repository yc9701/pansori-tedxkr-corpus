[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

# Pansori TEDxKR Corpus

The Pansori TEDxKR Corpus is Korean speech recognition (ASR) corpus dataset generated from Korean language TEDx talks given in Korea from 2010 to 2014. It contains about 3 hours of speech audio-transcript pairs from 41 speakers.

This corpus was generated by using a new corpus data ingestion and processing system called Pansori. Please refer to [this code repository](https://github.com/yc9701/pansori) and the following paper for further information on the Pansori ASR corpus generation system:

- Yoona Choi and Bowon Lee, "Pansori: ASR Corpus Generation from Open Online Video Contents," Proceedings of [IEEE Seoul Section Student Paper Contest 2018](http://sites.ieee.org/seoul/paper/), Hongik University, pp. 117--121, Nov. 2018.

Extra care was taken to maintain the quality of the generated corpus:

- Only TEDx talks hand transcribed by community translators were included.
- Corpus fragments were segmented at subtitle boundaries.
- Fine tuning segmentation by manual (tool-assisted) speech-text alignment.
- Final validation by state-of-the-art speech recognizer ([Google Cloud Speech-To-Text](https://cloud.google.com/speech-to-text/)).

The speech audio included in the corpus are 16 bit FLAC files with sampling rate of 16 KHz. Furrther information on the included speech contents is summarized in the following table:

| Title  | Speaker | Gender | Location | Year | Fragments | Duration |
|---|:-:|:-:|:-:|:-:|--:|--:|
| [Appropriate technology](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7J207ISx67KU/znxAJsY__HM) | 이성범 | M | Seoul | 2010 | 87 | 5:58 |
| [Making a village worth living in](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/6rmA7Zic7KCV/grgRnDg-o94) | 김혜정 | F | Busan  | 2012 | 191 | 9:14 |
| [The true owner of land](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/64Ko6riw7JeF/lvIVLOef9AM) | 남기업 | M | Busan  | 2012 | 155 | 6:43 |
| [Starting from where I am](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7Zmp65GQ7KeE/SP67ty4SXQA) | 황두진 | M | Seoul | 2010 | 117 | 6:41 |
| [Telling the new story in the old form](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7J207J6Q656M/D35qys8YZpo)  | 이자람 | F | Seoul | 2010 | 92 | 7:50 |
| [Dreaming a way to future aerial vehicle from unmanned aircraft](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/6rWs7IK87Jil/jUe7EdiQP1c) | 구삼옥 | M | Daedeok | 2011 | 121 | 7:34 |
| [Misconception about evaluations](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7Jyg7KCV7Iud/r7hLHMYQvp4) | 유정식 | M | Busan | 2012 | 158 | 6:43 |
| [Be an artist, right now!](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/6rmA7JiB7ZWY/zRvDWVfib2c) | 김영하 | M | Seoul | 2013 | 131 | 5:47 |
| [Communication is recovery](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/67CV7J6E7Iic/ZBNO2Drz36c) | 박임순 | F | Busan | 2012 | 161 | 6:24 |
| [Jeju Olleh](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7ISc66qF7IiZ/lGU_mqIdCAE) | 서명숙 | F | Seoul | 2010 | 135 | 9:16 |
| [DIY OOOSSSZZZ band](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7Jyg7IOB7KSA/FXJKQuElMnI) | 유상준 | M | Seoul | 2010 | 44 | 2:22 |
| [Dynamic biology](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7J207ISg7ZWY/vpDjbUl1nYQ) | 이선희 | F | Daedeok  | 2011 | 68 | 4:44 |
| [Active immersion in thinking](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7Zmp64aN66y4/beK1Iw23nc8) | 황농문 | M | Daejeon | 2012 | 84 | 5:01 |
| [Becoming a good-earthling](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7J207ZiE7KCV/R15jiXaSYik) | 이현정 | F | Busan | 2011 | 95 | 3:53 |
| [More humane medical experience](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7KCc6rmA7KCV/un4qbATrmx8) | 김승범, 정혜진 | M, F | Seoul | 2010 | 80 | 4:36 |
| [Finding new energy to overcome resource limits](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7J206rK97IiY/VvqkH7VUonQ) | 이경수 | M | Daejeon | 2010 | 53 | 4:43 |
| [Which do you love, pictures or camera?](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/67CV7Z2s7KeE/a7zuPg5if14) | 박희진 | M | Busan | 2014 | 38 | 2:42 |
| [Every citizen is a journalist](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7Jik7Jew7Zi4/XaE8qc5x5aY) | 오연호 | M | Seoul | 2010 | 61 | 4:10 |
| [Take time to imagine the world to rights](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7Jyk7ZWc6rKw/W-vbPHzNDKA) | 윤한결 | M | Busan | 2013 | 126 | 5:01 |
| [With feeling the aesthetics of slowness](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7J207IOB7J2A/43V_QSHvEP0) | 이상은 | F | Daejeon | 2011 | 29 | 3:45 |
| [Beating disabilities to pioneer grassroots journalism](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7KGw7KO87ZiE/Mcs_1DV6Sgc) | 조주현 | M | Daejeon | 2010 | 37 | 3:56 |
| [Statistics 3.0](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7J207J247Iuk/9j_HEK5nfyw) | 이인실 | F | Busan | 2011 | 94 | 3:42 |
| [Why Anlytical Science?](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7KCV6rSR7ZmU/Q4rvB0NaxGE) | 정광화 | F | Daedeok | 2011 | 58 | 3:56 |
| [Redefinition of soil and its possibilities](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7Iug6re87Iud/8-dSwR5iUyY) | 신근식 | M | Busan | 2011 | 76 | 3:51 |
| [Predict disease with face](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/6rmA7KKF7Je0/RMUVo-AZfQM) | 김종열 | M | Daedeok | 2011 | 72 | 4:08 |
| [Sustainable DoReMi](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/6rOg6rG07ZiB/aWPB0xeM8UA) | 고건혁 | M | Seoul | 2010 | 78 | 3:10 |
| [ITER, towards the dream of a fusion energy era](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7KCV6riw7KCV/GJu8ZETMTZU) | 정기정 | M | Daedeok | 2010 | 45 | 3:35 |
| [Winning the world with the 'DID' mindset](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7Iah7IiY7Jqp/2B1iXo1c1Tk) | 송수용 | M | Daejeon | 2010 | 66 | 3:19 |
| [Social venture is blue ocean](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/6rmA7KCV7ZiE/MJ0_NG4dsCY) | 김정현 | M | Busan | 2011 | 60 | 2:56 |
| [No prerequisite learning, no worry](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7Iug7ZiE7Iq5/YPdxHZmSU6M) | 신현승 | M | Busan | 2012 | 49 | 2:44 |
| [Passion and challenge](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7Iug7LC97Jew/GFYqXg0CriE) | 신창연 | M | Busan | 2011 | 88 | 2:46 |
| [Are science and liberal arts equal?](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/6rmA7IOB7Jqx/ccrZhrcWPLU) | 김상욱 | M | Busan | 2013 | 67 | 2:36 |
| [Perspective, music and life](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/64uk7LWc6rCc/Jihv3iSi53Q) | 다이나믹듀오 | M | Seoul | 2012 | 48 | 2:51 |
| [아이티 구호현장에서 발견한 음식의 가치](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/6rmA7J6s7ZWZ/rgUgvxlI_fk) | 김재학 | M | Seoul | 2010 | 8 | 0:25 |
| [A spirit of sharing information and culture 'CC'](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7LWc7KeE6raM/afP1mVVJYgw) | 최진권 | M | Daejeon | 2010 | 18 | 1:42 |
| [Gibbons, long-armed apes](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/6rmA7IKw7ZWY/Mwo47MAsMtE) | 김산하 | M | Seoul | 2010 | 73 | 2:22 |
| [Never let go of your passion, just keep working on it](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/6rmA64yA7Iud/E9cVSPWR9Ck) | 김대식 | M | Daejeon | 2010 | 23 | 1:50 |
| [Inconvenient truth of Korean Web](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/6rmA6riw7LC9/WRd7fHY3enA) | 김기창 | M | Busan | 2012 | 37 | 1:52 |
| [Statecraft, the art of conducting public affairs](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/7Jyk7Jes7KSA/LnGadr1MDs8) | 윤여준 | M | Seoul | 2010 | 46 | 1:59 |
| [Korean traditional hawk hunting](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/67CV7Jqp7Iic/zn8fTjUn_u8) | 박용순 | M | Daejeon | 2011 | 21 | 1:09 |
| [Multiple identity diaspora](https://github.com/yc9701/pansori-tedxkr-corpus/tree/master/6rmA6rK966y1/gwg56V-GEMQ) | 김경묵 | M | Seoul | 2010 | 1 | 0:12 |

The corpus can be downloaded either individually or as a whole from the GitHub repository. Alternatively, they are also available for download in one single archive file in the following link: [https://storage.googleapis.com/pansori/corpus/pansori-tedxkr-corpus-1.0.tar.gz](https://storage.googleapis.com/pansori/corpus/pansori-tedxkr-corpus-1.0.tar.gz) [170MB].

*We are currently preparing a large-sized Korean language ASR corpus by further automating the data processing pipeline used to generate this TEDxKR corpus. The new Korean ASR corpus will also be released under a permissive license once we confirm the types of license with the license holder.*
