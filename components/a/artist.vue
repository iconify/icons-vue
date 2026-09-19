<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iOfbCMc)" class="jm5_-zbfs"/><path fill="url(#iRa0jme)" class="jm5_-zbfs"/><path fill="url(#i0YxB1d)" class="jm5_-zbfs"/><path fill="url(#ijDgfCd)" class="jm5_-zbfs"/><g filter="url(#iE1hM7Z)"><path clip-rule="evenodd" class="vlpiorb9j"/></g><ellipse fill="url(#icTyT5b)" class="k_wcn2lfa"/><ellipse fill="url(#imdzlsc)" class="k_wcn2lfa"/><g filter="url(#i2jbhSd)"><ellipse stroke="url(#iBChO0s)" class="t781mubvm"/></g><g filter="url(#i7n95nd)"><path fill="url(#iSTnUgc)" class="rcf4twygv"/><path fill="url(#iSqh3xP)" class="rcf4twygv"/></g><g filter="url(#iVq1Qhb)"><path fill="url(#iEsaCGb)" class="lbk93bb3m"/><path fill="url(#ixeqiXu)" class="lbk93bb3m"/><path fill="url(#ilsKfcR)" class="lbk93bb3m"/></g><path fill="url(#iJnkKne)" class="qixp4vm-i"/><g filter="url(#iV3m6bd)"><path fill="url(#iA67Lxe)" class="bi60hruqh"/><path fill="url(#iTbrMlb)" class="bi60hruqh"/></g><path fill="url(#ibFP3mZ)" class="a3j8nte0r"/><path fill="url(#ixSAH4O)" class="a3j8nte0r"/><g filter="url(#iOSQuAd)"><path fill="url(#iYIKKbd)" class="z3dh2bb5s"/></g><g filter="url(#iovbwPc)"><path class="rvnl-832d"/></g><g filter="url(#iT9Nlrd)"><path class="sqj95vmrp"/></g><g filter="url(#iQ5N5Id)"><path class="tfb2xgb0r"/></g><g filter="url(#iYWf29d)"><path fill="url(#iQY071Z)" class="z46muhatr"/></g><path fill="url(#i1Wa42c)" class="z46muhatr"/><g filter="url(#iERnYid)"><path fill="url(#iCvra9b)" class="jzz4pabik"/></g><g filter="url(#i1bx0QZ)"><path fill="url(#iurF73c)" class="xctvn8crp"/></g><path fill="url(#il3BWId)" class="xctvn8crp"/><path fill="url(#i57dOkc)" class="whnai1bce"/><path fill="url(#iBTRSKd)" class="whnai1bce"/><path fill="url(#ibMQnMe)" class="eyg1mnrmn"/><path fill="url(#iYbOpob)" class="o8iot2brp"/><g filter="url(#izAKPUd)"><path fill="url(#iwv7ADb)" class="sk6ic1pcf"/></g><path fill="url(#iI2brLc)" class="sk6ic1pcf"/><path fill="url(#i3jZBEc)" class="sk6ic1pcf"/><path fill="url(#iVhncNd)" class="sk6ic1pcf"/><path fill="url(#isbtNQd)" class="sk6ic1pcf"/><path fill="url(#ihDyEOc)" class="sk6ic1pcf"/><path fill="url(#iJBUWVc)" class="sk6ic1pcf"/><g filter="url(#i5Rg7bb)"><path class="bk2p26b7y"/></g><g filter="url(#iF9e28b)"><path fill="url(#iXk7fYd)" class="mw5zkjmnt"/><path fill="url(#i95sO3m)" class="mw5zkjmnt"/><path fill="url(#iWPN3Ub)" class="mw5zkjmnt"/><path fill="url(#iZNwBfc)" class="mw5zkjmnt"/></g><g filter="url(#iluisJe)"><path stroke="url(#i7HqGcd)" class="fnduwz2em"/></g><path fill="url(#icXcsHd)" class="zc_lsn8eo"/><g filter="url(#iiza3Eb)"><path class="bh1laacyu"/></g><g filter="url(#iI5VWZd)"><path class="vksbihbpu"/></g><path class="t0v0swb7d"/><path fill="url(#iG7Yvze)" class="c4nrp-bqo"/><path class="osqlpy93e"/><g filter="url(#iVEmHsd)"><path class="m92d7f66e"/><path fill="url(#imkFCYc)" class="m9seo9b8i"/></g><g filter="url(#iFe5aOb)"><path fill="url(#ienzDIO)" class="p60so9jsa"/></g><path class="qhffjjblk"/><path fill="url(#iU4HOLb)" class="p42gd-bdn"/><path class="isxf5_b6b"/><g filter="url(#i43wl0b)"><path fill="url(#iyxelOb)" class="m72oudbzx"/></g><g filter="url(#isSbM6b)"><ellipse transform="rotate(-27.914 13.69 9.835)" class="dg9rozi8u"/><ellipse fill="url(#iXTqtrc)" transform="rotate(-27.914 13.69 9.835)" class="bee_sqafq"/></g><path fill="url(#iyNrzAs)" class="davk5-b1u"/><path fill="url(#iaCPolc)" class="davk5-b1u"/><path fill="url(#isGIIFb)" class="davk5-b1u"/><path fill="url(#iATZAdc)" class="zae43h__y"/><path fill="url(#ilf4Z8y)" class="zae43h__y"/><g filter="url(#iKGHFUd)"><path class="gitai3bum"/></g><g filter="url(#izlRlna)"><path class="o8vt64lnl"/></g><g filter="url(#iI4T85c)"><path class="t12a8_qgv"/></g><g filter="url(#irKTuNe)"><path class="fieajvbur"/></g><path fill="url(#i5ztI2c)" class="c9bz1fqqv"/><path fill="url(#itTAxmd)" class="c9bz1fqqv"/><path class="ub3fdabpz"/><path fill="url(#ikH3fls)" class="u-iovl2-y"/><path class="luwneybob"/><path fill="url(#iuI7BMb)" class="vmv1-nbfg"/><g filter="url(#iDJSgYx)"><path fill="url(#iCJe3gd)" class="s3pn0xbaq"/></g><g filter="url(#iKjHP3G)"><path fill="url(#iKDWVyb)" class="i80rddczw"/></g><g filter="url(#ixW4Juo)"><path fill="url(#ix22Z9j)" class="h9tx_sggc"/><path fill="url(#ilzuLld)" class="h9tx_sggc"/></g><path fill="url(#iZXjjcb)" class="dv6oekb0u"/><path fill="url(#ioPmddc)" class="dv6oekb0u"/><path fill="url(#iqEd2Pc)" class="dv6oekb0u"/><path fill="url(#iqS8ILc)" class="bu6fge8bs"/><path fill="url(#irIwknA)" class="bu6fge8bs"/><g filter="url(#iXgoHqb)"><path fill="url(#iWpkzyc)" class="m4j2h0bed"/><path fill="url(#ioi60le)" class="m4j2h0bed"/><path fill="url(#iv4xIue)" class="m4j2h0bed"/><path fill="url(#iJb3ykd)" class="m4j2h0bed"/></g><path fill="url(#iQr5dvL)" class="abcb8pyla"/><g filter="url(#irqmWRd)"><path fill="url(#i12Hwoc)" class="paghoubuj"/><path fill="url(#iJ3ID3c)" class="paghoubuj"/><path fill="url(#ijMEnds)" class="paghoubuj"/><path fill="url(#iDDrk4d)" class="paghoubuj"/></g><g filter="url(#ioe8lEM)"><path fill="url(#i7UmOUc)" class="yz5elgb0p"/><path fill="url(#icq5kke)" class="yz5elgb0p"/><path fill="url(#iFP2ovd)" class="yz5elgb0p"/><path fill="url(#iRUoabc)" class="yz5elgb0p"/><path fill="url(#inthXpi)" class="yz5elgb0p"/></g><g filter="url(#irUYGQv)"><path stroke="url(#imIbKVb)" class="hls_d4b8p"/></g><g filter="url(#iE4a8jc)"><path stroke="url(#iCTkw9d)" class="j5haylkls"/></g><g filter="url(#iWXdsCb)"><path stroke="url(#iw0FQlL)" class="i5nvcfbap"/></g><defs><radialGradient id="iOfbCMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5008 14.4291 0 19.814 29.95)" gradientUnits="userSpaceOnUse"><stop class="vq38zyg1v"/><stop offset=".574" class="xc8aunbib"/></radialGradient><radialGradient id="iRa0jme" cx="0" cy="0" r="1" gradientTransform="matrix(6.25665 1.2745 -1.23055 6.0409 8.305 19.487)" gradientUnits="userSpaceOnUse"><stop class="wb9dsybrx"/><stop offset="1" class="ahmnpcbvc"/></radialGradient><radialGradient id="i0YxB1d" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6815 -14.49994 16.74587 -7.7164 19.235 29.95)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="ue4dcor2v"/><stop offset="1" class="l7qllmb5o"/></radialGradient><radialGradient id="ijDgfCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.5561 -3.36712 0 23.143 21.186)" gradientUnits="userSpaceOnUse"><stop class="smyxk1pmd"/><stop offset="1" class="g5cj4-btu"/></radialGradient><radialGradient id="imdzlsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.9375 -5.90625 0 16.143 16.697)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ta7eky02w"/><stop offset="1" class="j0piksb8i"/></radialGradient><radialGradient id="iSTnUgc" cx="0" cy="0" r="1" gradientTransform="rotate(121.17 1.812 14.729)scale(3.39503 1.76158)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b_wctrb8k"/><stop offset=".826" class="q90xsjbgn"/></radialGradient><radialGradient id="iSqh3xP" cx="0" cy="0" r="1" gradientTransform="rotate(68.848 -6.403 21.01)scale(1.84199 .94148)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="jvqqj3hdm"/><stop offset="1" class="w_jg8bumh"/></radialGradient><radialGradient id="iEsaCGb" cx="0" cy="0" r="1" gradientTransform="rotate(62.84 -7.483 24.68)scale(4.03912 1.93026)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="ccy1m_asd"/><stop offset="1" class="yan0zenen"/></radialGradient><radialGradient id="ilsKfcR" cx="0" cy="0" r="1" gradientTransform="matrix(.66907 .71875 -.43642 .40625 18.111 20.525)" gradientUnits="userSpaceOnUse"><stop class="pjwz_ic9q"/><stop offset="1" class="acw_xab5u"/></radialGradient><radialGradient id="iJnkKne" cx="0" cy="0" r="1" gradientTransform="rotate(-60.439 22.083 5.047)scale(4.7509 1.9254)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="glav2bc0u"/><stop offset="1" class="p_p7u6byq"/></radialGradient><radialGradient id="iTbrMlb" cx="0" cy="0" r="1" gradientTransform="matrix(-.44275 1.19364 -.36328 -.13475 17.117 19.463)" gradientUnits="userSpaceOnUse"><stop class="eq8448bna"/><stop offset="1" class="qn-z6_0fu"/></radialGradient><radialGradient id="iQY071Z" cx="0" cy="0" r="1" gradientTransform="matrix(-.26 1.96876 -1.77419 -.2343 8.643 23.291)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="f82vlntau"/><stop offset="1" class="d1l_oobjb"/></radialGradient><radialGradient id="i1Wa42c" cx="0" cy="0" r="1" gradientTransform="rotate(-39.218 38.087 .863)scale(1.7546 2.0006)" gradientUnits="userSpaceOnUse"><stop offset=".574" class="mbdolbbcq"/><stop offset="1" class="hdm7u0bdo"/></radialGradient><radialGradient id="iCvra9b" cx="0" cy="0" r="1" gradientTransform="matrix(1.23999 2.33168 -1.89085 1.00556 11.383 25.758)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="j-p-7tbjt"/><stop offset="1" class="ku_74wg1j"/></radialGradient><radialGradient id="iurF73c" cx="0" cy="0" r="1" gradientTransform="rotate(133.958 -1.602 15.3)scale(2.43108 1.88477)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="ukhbhfbdb"/><stop offset="1" class="ngwdu-l5j"/></radialGradient><radialGradient id="il3BWId" cx="0" cy="0" r="1" gradientTransform="matrix(1.8081 -.98438 1.04155 1.91313 6.814 28.338)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="tx_tdxoal"/><stop offset="1" class="j_c7fcbhg"/></radialGradient><radialGradient id="i57dOkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42193 -3.27267 0 16.143 17.07)" gradientUnits="userSpaceOnUse"><stop offset=".395" class="a_iq15w2m"/><stop offset="1" class="vl4d3lbhw"/></radialGradient><radialGradient id="iBTRSKd" cx="0" cy="0" r="1" gradientTransform="matrix(3.94043 .98437 -.58167 2.32843 14.233 16.541)" gradientUnits="userSpaceOnUse"><stop offset=".866" class="fp7gzobqh"/><stop offset=".952" class="r3gzp2rve"/></radialGradient><radialGradient id="ibMQnMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.77581 -2.40247 0 20.818 11.963)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="lelniimio"/><stop offset="1" class="cx9qd4b4i"/></radialGradient><radialGradient id="iYbOpob" cx="0" cy="0" r="1" gradientTransform="matrix(.01563 2.69768 -.62543 .00362 11.236 12.041)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="l9n5x633m"/><stop offset="1" class="be8sk-xyt"/></radialGradient><radialGradient id="iwv7ADb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24801 18.95 10.847)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iI2brLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40256 6.10192 -2.24332 -.148 21.3 10.616)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="i3jZBEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41386 1.70221 0 14.051 9.667)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iVhncNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53524 1.99125 0 18.631 9.255)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="isbtNQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.2596 -13.1867 0 16.19 7.235)" gradientUnits="userSpaceOnUse"><stop offset=".758" class="m5yjveb4h"/><stop offset="1" class="wve9iuv6p"/></radialGradient><radialGradient id="ihDyEOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.72499 -9.99624 0 16.19 8.499)" gradientUnits="userSpaceOnUse"><stop offset=".952" class="pcao0ul7r"/><stop offset="1" class="aqkh50f-t"/></radialGradient><radialGradient id="i7HqGcd" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.572 -5.746)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="icXcsHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 16.142 14.387)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iG7Yvze" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.325 9.931)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="imkFCYc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.5 .576)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iU4HOLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.96 9.931)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iXTqtrc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.674 10.15)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iaCPolc" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.76 9.945)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="isGIIFb" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.12 10.49)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="ilf4Z8y" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.29 9.52)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="i5ztI2c" cx="0" cy="0" r="1" gradientTransform="matrix(.38892 2.02343 -.51934 .09982 21.504 6.596)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="y2f89vcbj"/><stop offset=".997" class="m8d4chqek"/></radialGradient><radialGradient id="itTAxmd" cx="0" cy="0" r="1" gradientTransform="matrix(.45313 1.19532 -.43713 .16571 20.877 6.994)" gradientUnits="userSpaceOnUse"><stop offset=".327" class="jo7oa2b4e"/><stop offset="1" class="pbkp8utnv"/></radialGradient><radialGradient id="ikH3fls" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.55469 -.97302 0 11.455 7.025)" gradientUnits="userSpaceOnUse"><stop class="u2vudgbww"/><stop offset=".544" class="qk4xm-bhz"/><stop offset="1" class="kj5z24bpf"/></radialGradient><radialGradient id="iuI7BMb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.66487 -5.81608 0 15.975 6.549)" gradientUnits="userSpaceOnUse"><stop class="j-4y6njnd"/><stop offset="1" class="mywg7wbjh"/></radialGradient><radialGradient id="iCJe3gd" cx="0" cy="0" r="1" gradientTransform="matrix(8.99875 0 0 2.97087 15.952 4.345)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><radialGradient id="iKDWVyb" cx="0" cy="0" r="1" gradientTransform="rotate(170.731 6.378 3.22)scale(6.59378 2.26941)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><radialGradient id="ix22Z9j" cx="0" cy="0" r="1" gradientTransform="rotate(117.802 7.159 20.2)scale(1.88642 1.51516)" gradientUnits="userSpaceOnUse"><stop class="id09adcid"/><stop offset=".828" class="gtmq6ja1j"/></radialGradient><radialGradient id="ilzuLld" cx="0" cy="0" r="1" gradientTransform="rotate(-44.734 43.591 -21.05)scale(.59387 .63238)" gradientUnits="userSpaceOnUse"><stop class="xcc0mcchc"/><stop offset="1" class="lyxdnwxxe"/></radialGradient><radialGradient id="iZXjjcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.44558 -1.78271 0 25.143 23.504)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="nqi0jc4ki"/><stop offset="1" class="vbxkmpbas"/></radialGradient><radialGradient id="iqS8ILc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.03125 -1.25369 0 27.018 21.76)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="jujuy5bla"/><stop offset="1" class="e7xip1bbn"/></radialGradient><radialGradient id="ioi60le" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.22231 -.54688 0 26.69 18.71)" gradientUnits="userSpaceOnUse"><stop class="qbo0gacsu"/><stop offset="1" class="codu-dcmv"/></radialGradient><radialGradient id="iv4xIue" cx="0" cy="0" r="1" gradientTransform="matrix(-.03572 .55078 -.83966 -.05446 26.389 18.79)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="y3oq4nb4y"/><stop offset="1" class="js7kctros"/></radialGradient><radialGradient id="iQr5dvL" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38869 -2.63745 3.16971 -1.66894 27.232 19.1)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="d7q2h2w-e"/><stop offset="1" class="wxo_vcdjw"/></radialGradient><radialGradient id="i12Hwoc" cx="0" cy="0" r="1" gradientTransform="rotate(149.211 11.543 12.316)scale(2.25809 2.54697)" gradientUnits="userSpaceOnUse"><stop class="tm2bmw9uh"/><stop offset="1" class="zxeleub3j"/></radialGradient><radialGradient id="iJ3ID3c" cx="0" cy="0" r="1" gradientTransform="rotate(-157.433 16.012 5.582)scale(2.84995 2.97831)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="l21dfeb9j"/><stop offset="1" class="el-cg1bcl"/></radialGradient><radialGradient id="ijMEnds" cx="0" cy="0" r="1" gradientTransform="matrix(.68035 .40317 -.6454 1.0891 28.672 15.586)" gradientUnits="userSpaceOnUse"><stop offset=".642" class="vn0ta5bom"/><stop offset="1" class="y_e8mrzhh"/></radialGradient><radialGradient id="iDDrk4d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0009 1.0903 -.16655 -.1529 28.4 14.71)" gradientUnits="userSpaceOnUse"><stop class="jyboxmbnp"/><stop offset="1" class="v3wx_yddl"/></radialGradient><radialGradient id="icq5kke" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 28.323 24.543)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="iFP2ovd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 24.191 25.92)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="iRUoabc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 24.005 27.246)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="inthXpi" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 23.91 28.513)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><filter id="iE1hM7Z" width="10.518" height="10.531" x="10.051" y="14.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".75"/></filter><filter id="i2jbhSd" width="8.987" height="5.737" x="11.649" y="14.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".2"/></filter><filter id="i7n95nd" width="2.812" height="4.17" x="13.354" y="19.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.0588235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2382"/></filter><filter id="iVq1Qhb" width="2.762" height="4.17" x="16.118" y="19.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.0470588 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2382"/></filter><filter id="iV3m6bd" width="2.05" height="1.794" x="15.167" y="18.862" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.0941176 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2382"/></filter><filter id="iOSQuAd" width="10.434" height="8.872" x="4.246" y="21.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.988235 0 0 0 0 0.678431 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2382"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.832289 0 0 0 0 0.679486 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2382" result="effect2_innerShadow_4002_2382"/></filter><filter id="iovbwPc" width="2.78" height="2.78" x="6.922" y="22.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".075"/></filter><filter id="iT9Nlrd" width="2.78" height="2.78" x="9.93" y="25.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".075"/></filter><filter id="iQ5N5Id" width="2.78" height="2.78" x="5.919" y="26.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".075"/></filter><filter id="iYWf29d" width="2.58" height="2.68" x="7.143" y="22.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2382"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2382" result="effect2_innerShadow_4002_2382"/></filter><filter id="iERnYid" width="2.58" height="2.68" x="10.143" y="25.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.615686 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2382"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.427451 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2382" result="effect2_innerShadow_4002_2382"/></filter><filter id="i1bx0QZ" width="2.58" height="2.68" x="6.143" y="26.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.733333 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2382"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.596078 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2382" result="effect2_innerShadow_4002_2382"/></filter><filter id="izAKPUd" width="10.72" height="12.542" x="11.079" y="4.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2382"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2382" result="effect2_innerShadow_4002_2382"/></filter><filter id="i5Rg7bb" width="3.604" height="4.819" x="13.997" y="9.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".5"/></filter><filter id="iF9e28b" width="2.077" height="3.1" x="15.104" y="9.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".05"/></filter><filter id="iluisJe" width="3.718" height="1.573" x="14.283" y="13.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".05"/></filter><filter id="iiza3Eb" width="2.339" height="1.19" x="17.732" y="7.164" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2382"/></filter><filter id="iI5VWZd" width="2.339" height="1.176" x="12.475" y="7.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2382"/></filter><filter id="iVEmHsd" width=".787" height=".696" x="17.59" y="9.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".05"/></filter><filter id="iFe5aOb" width=".891" height=".913" x="18.43" y="9.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".1"/></filter><filter id="i43wl0b" width=".986" height="1.04" x="13.988" y="9.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".1"/></filter><filter id="isSbM6b" width=".913" height=".705" x="13.233" y="9.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".05"/></filter><filter id="iKGHFUd" width="1.329" height="2.379" x="10.11" y="9.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".125"/></filter><filter id="izlRlna" width="1.447" height="2.403" x="20.854" y="9.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".125"/></filter><filter id="iI4T85c" width="2.205" height=".96" x="12.494" y="7.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".1"/></filter><filter id="irKTuNe" width="2.188" height=".951" x="17.773" y="7.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".1"/></filter><filter id="iDJSgYx" width="9.346" height="5.558" x="14.326" y="1.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".5"/></filter><filter id="iKjHP3G" width="7.084" height="4.956" x="8.009" y="3.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".75"/></filter><filter id="ixW4Juo" width="2.584" height="3.682" x="26.767" y="22.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.560784 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2382"/></filter><filter id="iXgoHqb" width="2.15" height="1.99" x="25.327" y="18.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2382"/></filter><filter id="irqmWRd" width="3.363" height="3.394" x="25.088" y="14.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.501961 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2382"/></filter><filter id="ioe8lEM" width="4.996" height="5.556" x="24.005" y="24.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.513726 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2382"/></filter><filter id="irUYGQv" width="2.047" height=".25" x="24.4" y="25.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".05"/></filter><filter id="iE4a8jc" width="2.047" height=".25" x="24.322" y="27.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".05"/></filter><filter id="iWXdsCb" width="2.047" height=".25" x="24.4" y="28.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2382" stdDeviation=".05"/></filter><linearGradient id="icTyT5b" x1="15.111" x2="19.58" y1="17.854" y2="17.854" gradientUnits="userSpaceOnUse"><stop class="qob7fubko"/><stop offset="1" class="g9vtwf9nq"/></linearGradient><linearGradient id="iBChO0s" x1="13.162" x2="19.751" y1="17.666" y2="17.666" gradientUnits="userSpaceOnUse"><stop class="pr-l-mb5c"/><stop offset="1" class="bfk53cc2r"/></linearGradient><linearGradient id="ixeqiXu" x1="16.549" x2="17.449" y1="19.033" y2="20.76" gradientUnits="userSpaceOnUse"><stop offset=".106" class="a4kimk95l"/><stop offset="1" class="z6d28bbdt"/></linearGradient><linearGradient id="iA67Lxe" x1="16.342" x2="16.342" y1="20.389" y2="18.962" gradientUnits="userSpaceOnUse"><stop class="rcioyubpk"/><stop offset=".514" class="idowujb9l"/><stop offset="1" class="hhz1a6b2j"/></linearGradient><linearGradient id="ibFP3mZ" x1="8.366" x2="8.366" y1="21.078" y2="29.949" gradientUnits="userSpaceOnUse"><stop class="ejom4oo7z"/><stop offset=".389" class="qmqo746eg"/><stop offset="1" class="kprsiwbrh"/></linearGradient><linearGradient id="ixSAH4O" x1="5.346" x2="5.346" y1="29.949" y2="29.574" gradientUnits="userSpaceOnUse"><stop class="gnozolbql"/><stop offset="1" class="vnvkvjbds"/></linearGradient><linearGradient id="iYIKKbd" x1="9.413" x2="9.413" y1="21.078" y2="29.949" gradientUnits="userSpaceOnUse"><stop class="n4l67hb-g"/><stop offset="1" class="lacq-oqha"/></linearGradient><linearGradient id="iJBUWVc" x1="16.189" x2="16.189" y1="6.776" y2="7.508" gradientUnits="userSpaceOnUse"><stop class="r9q9pn73s"/><stop offset="1" class="ii1a0-b3q"/></linearGradient><linearGradient id="iXk7fYd" x1="16.142" x2="16.997" y1="11.676" y2="11.676" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="i95sO3m" x1="15.07" x2="16.144" y1="11.521" y2="11.58" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iWPN3Ub" x1="16.142" x2="16.142" y1="12.075" y2="12.927" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iZNwBfc" x1="16.142" x2="16.142" y1="9.827" y2="10.247" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="ienzDIO" x1="19.102" x2="18.789" y1="9.985" y2="10.178" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyxelOb" x1="14.704" x2="14.391" y1="9.985" y2="10.178" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyNrzAs" x1="22.579" x2="21.372" y1="10.012" y2="12.188" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iATZAdc" x1="10.293" x2="11.751" y1="10.716" y2="10.589" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="ioPmddc" x1="22.942" x2="24.912" y1="24.585" y2="24.43" gradientUnits="userSpaceOnUse"><stop class="juq22w2kb"/><stop offset="1" class="c5twxuzif"/></linearGradient><linearGradient id="iqEd2Pc" x1="23.831" x2="23.831" y1="30.649" y2="28.177" gradientUnits="userSpaceOnUse"><stop class="u8zhdtbla"/><stop offset="1" class="izb4o5hjh"/></linearGradient><linearGradient id="irIwknA" x1="26.353" x2="26.353" y1="20.699" y2="20.783" gradientUnits="userSpaceOnUse"><stop class="m9kxmpbyp"/><stop offset="1" class="nofcsmmpr"/></linearGradient><linearGradient id="iWpkzyc" x1="26.353" x2="27.83" y1="19.353" y2="19.353" gradientUnits="userSpaceOnUse"><stop class="fbd1ljb8v"/><stop offset="1" class="rubvd1wqd"/></linearGradient><linearGradient id="iJb3ykd" x1="26.502" x2="26.502" y1="20.699" y2="20.639" gradientUnits="userSpaceOnUse"><stop class="af9b0l-ho"/><stop offset="1" class="yck9m-swa"/></linearGradient><linearGradient id="i7UmOUc" x1="28.033" x2="24.005" y1="28.012" y2="28.012" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="xwbtobibq"/></linearGradient><linearGradient id="imIbKVb" x1="26.205" x2="24.369" y1="25.927" y2="25.927" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iCTkw9d" x1="26.127" x2="24.291" y1="27.232" y2="27.232" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iw0FQlL" x1="26.205" x2="24.369" y1="28.536" y2="28.536" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:artist" /></template>
<style>
.a_iq15w2m {
  stop-color: var(--svg-color--f98b29, #F98B29);
}

.a3j8nte0r {
  d: path("M4.59 29.95h8.843l-2.031-5.805c-.602-1.791-.32-3.533-4.61-2.954c-2.718.333-4.203 3.217-3.156 6.123z");
}

.a4kimk95l {
  stop-color: var(--svg-color--e73a62, #E73A62);
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abcb8pyla {
  d: path("m25.169 16.554l.685-.092c.322 0 .735.471.735.794c0 .473.136.55.609.55c.454.01.86 0 .907-.436q.005.058.005.117a1.61 1.61 0 0 1-1.613 1.613a1.61 1.61 0 0 1-1.43-2.355c.01-.022.091-.17.102-.19");
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.acw_xab5u {
  stop-color: var(--svg-color--ed577d, #ED577D);
  stop-opacity: 0;
}

.af9b0l-ho {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.ahmnpcbvc {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
  stop-opacity: 0;
}

.aqkh50f-t {
  stop-color: var(--svg-color--f2734d, #F2734D);
}

.b_wctrb8k {
  stop-color: var(--svg-color--d2418b, #D2418B);
}

.b45v6hbpx {
  stop-color: var(--svg-color--66606e, #66606E);
}

.be8sk-xyt {
  stop-color: var(--svg-color--e28333, #E28333);
}

.bee_sqafq {
  cx: 13.689px;
  cy: 9.835px;
  rx: 0.39px;
  ry: 0.197px;
}

.bfk53cc2r {
  stop-color: var(--svg-color--f4527c, #F4527C);
}

.bh1laacyu {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M19.875 7.868a1.85 1.85 0 0 0-.687-.412c-.304-.095-.685-.121-1.213-.057a.277.277 0 1 0 .068.55c.48-.058.776-.027.978.036c.199.063.333.164.49.301a.277.277 0 1 0 .364-.418");
}

.bi60hruqh {
  d: path("M15.413 19.072a2.4 2.4 0 0 1 .729-.11c.297 0 .546.051.729.11c.185.059.277.25.236.441a4 4 0 0 1-.222.714a.69.69 0 0 1-.609.426c-.12.005-.148.005-.27 0a.69.69 0 0 1-.607-.426a4 4 0 0 1-.223-.714c-.04-.19.052-.382.237-.441");
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bk2p26b7y {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.656 10.328l-.635 1.839c-.108.378.152.756.521.756h.786c.37 0 .29-.307.182-.679l-.508-1.719c-.114-.407-.226-.604-.346-.197");
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.bu6fge8bs {
  d: path("M25.378 20.7a.1.1 0 0 0-.098.082c-.23 1.338-.199 2.695-.107 4.134l.61 4.303c.04.28.286.5.571.5c.297 0 .541-.21.572-.5l.63-4.35c.06-1.493.092-2.752-.137-4.087a.1.1 0 0 0-.098-.083z");
}

.c4nrp-bqo {
  d: path("M18.327 9.454a.892.892 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.c5twxuzif {
  stop-color: var(--svg-color--cfc7d3, #CFC7D3);
  stop-opacity: 0;
}

.c9bz1fqqv {
  d: path("M20.728 6.908c.183.151.547.586.547 1.117c0 .323-.024.68-.035.97c.182.032.369.099.524.187c.003-.292.045-.7.14-.989c.048-.146.104-.28.157-.408c.158-.382.296-.716.167-1.19h-1.5z");
}

.ccy1m_asd {
  stop-color: var(--svg-color--e2457f, #E2457F);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.codu-dcmv {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
  stop-opacity: 0;
}

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
  stop-opacity: 0;
}

.cx9qd4b4i {
  stop-color: var(--svg-color--ff9642, #FF9642);
}

.d1l_oobjb {
  stop-color: var(--svg-color--f52884, #F52884);
}

.d7q2h2w-e {
  stop-color: var(--svg-color--eba287, #EBA287);
}

.davk5-b1u {
  d: path("M21.064 12.188q.1-1.596.185-3.19a1.61 1.61 0 0 1-.185 3.19");
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dg9rozi8u {
  cx: 13.689px;
  cy: 9.835px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.dv6oekb0u {
  d: path("M23.143 29.95v-12c2.44 2.023 4 5.078 4 8.493v3.506z");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e7xip1bbn {
  stop-color: var(--svg-color--7a424b, #7A424B);
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.ejom4oo7z {
  stop-color: var(--svg-color--d6a87f, #D6A87F);
}

.el-cg1bcl {
  stop-color: var(--svg-color--499da3, #499DA3);
}

.eq8448bna {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
}

.eyg1mnrmn {
  d: path("M21.004 12.097c.335-.01.649-.124.904-.308v.93c0 .894-.532 1.69-1.34 2.02q.257-.546.345-1.18z");
}

.f82vlntau {
  stop-color: var(--svg-color--ff54ab, #FF54AB);
}

.fbd1ljb8v {
  stop-color: var(--svg-color--9689a5, #9689A5);
}

.fieajvbur {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.686 8.018c-.274-.255-.88-.493-1.638-.366");
}

.fnduwz2em {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.792 13.349c.39.203.855.32 1.35.32c.501 0 .961-.117 1.351-.32h.001a.23.23 0 0 1 .27.044a.214.214 0 0 1 .024.273m-2.996-.317l2.934.275m-2.934-.275a.23.23 0 0 0-.272.046a.21.21 0 0 0-.023.271m.295-.317l-.233.275m3.23.042l-.063-.042m.062.042l-.062-.042m.062.042c-.348.528-.955.88-1.646.88c-.69 0-1.296-.352-1.645-.88m3.229-.042a1.9 1.9 0 0 1-1.584.846a1.9 1.9 0 0 1-1.583-.846m-.062.042v.001l.062-.043m-.062.042l.062-.042");
}

.fp7gzobqh {
  stop-color: var(--svg-color--ba4810, #BA4810);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g5cj4-btu {
  stop-color: var(--svg-color--d5c0de, #D5C0DE);
  stop-opacity: 0;
}

.g9vtwf9nq {
  stop-color: var(--svg-color--f22749, #F22749);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gitai3bum {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M11.105 9.65a.956.956 0 0 0 .084 1.879a78 78 0 0 1-.084-1.88");
}

.glav2bc0u {
  stop-color: var(--svg-color--b0aaae, #B0AAAE);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gnozolbql {
  stop-color: var(--svg-color--dd929a, #DD929A);
}

.gtmq6ja1j {
  stop-color: var(--svg-color--ffd235, #FFD235);
}

.gzbsswvik {
  stop-color: var(--svg-color--f9a42e, #F9A42E);
}

.h9tx_sggc {
  d: path("M27.734 22.993a.97.97 0 0 1 .967.967v2.215h-1.934V23.96a.976.976 0 0 1 .967-.967");
}

.hdm7u0bdo {
  stop-color: var(--svg-color--ff87c1, #FF87C1);
}

.hhz1a6b2j {
  stop-color: var(--svg-color--d72a4d, #D72A4D);
}

.hls_d4b8p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M24.525 25.927h1.797");
}

.i5nvcfbap {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M24.525 28.536h1.797");
}

.i80rddczw {
  d: path("M13.015 4.7c-.973-.092-2.504.104-3.147.213c-.174.135-.48.54-.31 1.082c.17.54.574.65.754.637c3.302-.637 3.92-1.815 2.703-1.931");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.id09adcid {
  stop-color: var(--svg-color--ffe047, #FFE047);
}

.idowujb9l {
  stop-color: var(--svg-color--d83864, #D83864);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ii1a0-b3q {
  stop-color: var(--svg-color--f19a2a, #F19A2A);
  stop-opacity: 0;
}

.isxf5_b6b {
  fill: var(--svg-color--000, #000);
  d: path("M14.47 10.347a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .06-.235");
}

.izb4o5hjh {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
  stop-opacity: 0;
}

.j_c7fcbhg {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
}

.j-4y6njnd {
  stop-color: var(--svg-color--41225a, #41225A);
}

.j-p-7tbjt {
  stop-color: var(--svg-color--5eccf3, #5ECCF3);
}

.j0piksb8i {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
}

.j5haylkls {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M24.447 27.232h1.797");
}

.jm5_-zbfs {
  d: path("M9.143 17.964a10.96 10.96 0 0 1 7-2.515c2.658 0 5.097.944 7 2.515v11.985h-14z");
}

.jo7oa2b4e {
  stop-color: var(--svg-color--ff9d39, #FF9D39);
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.js7kctros {
  stop-color: var(--svg-color--97769c, #97769C);
  stop-opacity: 0;
}

.jujuy5bla {
  stop-color: var(--svg-color--8e5e5c, #8E5E5C);
}

.juq22w2kb {
  stop-color: var(--svg-color--ab95b9, #AB95B9);
}

.jvqqj3hdm {
  stop-color: var(--svg-color--c01b54, #C01B54);
}

.jyboxmbnp {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
}

.jzz4pabik {
  d: path("M11.383 28.238a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.k_wcn2lfa {
  cx: 16.143px;
  cy: 17.289px;
  rx: 4.489px;
  ry: 3.08px;
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.kj5z24bpf {
  stop-color: var(--svg-color--f1863a, #F1863A);
  stop-opacity: 0;
}

.kprsiwbrh {
  stop-color: var(--svg-color--e2a291, #E2A291);
}

.ku_74wg1j {
  stop-color: var(--svg-color--4a96ee, #4A96EE);
}

.l21dfeb9j {
  stop-color: var(--svg-color--499da3, #499DA3);
  stop-opacity: 0;
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.l7qllmb5o {
  stop-color: var(--svg-color--afa1a1, #AFA1A1);
}

.l9n5x633m {
  stop-color: var(--svg-color--ff9620, #FF9620);
}

.lacq-oqha {
  stop-color: var(--svg-color--ffc8a9, #FFC8A9);
}

.lbk93bb3m {
  d: path("M18.221 19.932c-.824-.79-1.717-.938-2.058-.891c-.133 1.793.011 2.527.722 3.309c.425.466 1.055.722 1.51.843c.204.054.388-.108.385-.318c-.004-.362-.012-.844-.016-1.104c0-.628-.02-1.308-.543-1.84");
}

.lelniimio {
  stop-color: var(--svg-color--ffce38, #FFCE38);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.luwneybob {
  fill: var(--svg-color--352b40, #352B40);
  d: path("M9.007 5.81c0-.45.344-.983.734-1.213c1.816-1.27 5.57-2.66 8.778-2.595c2.738.15 4.324 1.637 4.424 4.156c.019.491-.534.791-.934.791H10.264c-.685 0-1.257-.43-1.257-1.14");
}

.lyxdnwxxe {
  stop-color: var(--svg-color--efa20d, #EFA20D);
  stop-opacity: 0;
}

.m4j2h0bed {
  d: path("M27.277 20.7a.1.1 0 0 0 .098-.115a11.6 11.6 0 0 0-.432-1.876h-1.2a10.3 10.3 0 0 0-.415 1.879a.1.1 0 0 0 .098.111z");
}

.m5yjveb4h {
  stop-color: var(--svg-color--f89d39, #F89D39);
  stop-opacity: 0;
}

.m72oudbzx {
  d: path("M14.774 10.242c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.m8d4chqek {
  stop-color: var(--svg-color--ffb730, #FFB730);
}

.m92d7f66e {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.26 9.643c.064.085-.068.188-.22.301c-.15.113-.263.193-.326.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.m9kxmpbyp {
  stop-color: var(--svg-color--603a3e, #603A3E);
}

.m9seo9b8i {
  d: path("M18.26 9.643c.064.085-.068.188-.22.301c-.15.113-.263.193-.326.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.mbdolbbcq {
  stop-color: var(--svg-color--ff5aaa, #FF5AAA);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mw5zkjmnt {
  d: path("m15.76 10.133l-.531 1.838c-.109.378.152.756.52.756h.787c.368 0 .629-.383.52-.756l-.531-1.838c-.114-.407-.645-.407-.765 0");
}

.mywg7wbjh {
  stop-color: var(--svg-color--41225a, #41225A);
  stop-opacity: 0;
}

.n2f566bzz {
  stop-color: var(--svg-color--66606e, #66606E);
  stop-opacity: 0;
}

.n4l67hb-g {
  stop-color: var(--svg-color--ffcdab, #FFCDAB);
}

.ngwdu-l5j {
  stop-color: var(--svg-color--4fdda1, #4FDDA1);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nofcsmmpr {
  stop-color: var(--svg-color--603a3e, #603A3E);
  stop-opacity: 0;
}

.nqi0jc4ki {
  stop-color: var(--svg-color--e5dfed, #E5DFED);
}

.o8iot2brp {
  d: path("M11.281 12.097a1.64 1.64 0 0 1-.904-.308v.93c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.o8vt64lnl {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M21.104 11.537q.059-.952.11-1.903a.956.956 0 0 1-.11 1.903");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.osqlpy93e {
  fill: var(--svg-color--000, #000);
  d: path("M17.815 10.347a.51.51 0 0 1 .512-.512a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.06-.235");
}

.p_p7u6byq {
  stop-color: var(--svg-color--989295, #989295);
}

.p42gd-bdn {
  d: path("M13.958 9.454a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.p60so9jsa {
  d: path("M19.122 10.23a.84.84 0 0 0-.232-.464l-.26.286l.117.228z");
}

.paghoubuj {
  d: path("M28.293 14.874a.33.33 0 0 0-.215-.075c-1.248.083-2.375.65-2.978 1.74a.096.096 0 0 0 .086.141h.634c.322 0 .58.259.58.581c0 .473.366.882.839.882c.473.01.85-.366.87-.828a1 1 0 0 0-.02-.161v-.011c-.162-.699-.054-1.29.279-1.882a.33.33 0 0 0-.075-.387");
}

.pbkp8utnv {
  stop-color: var(--svg-color--ff9d39, #FF9D39);
  stop-opacity: 0;
}

.pcao0ul7r {
  stop-color: var(--svg-color--f2734d, #F2734D);
  stop-opacity: 0;
}

.pjwz_ic9q {
  stop-color: var(--svg-color--ed577d, #ED577D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pr-l-mb5c {
  stop-color: var(--svg-color--cf316b, #CF316B);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q0u2bl4sa {
  stop-color: var(--svg-color--f9a42e, #F9A42E);
  stop-opacity: 0;
}

.q90xsjbgn {
  stop-color: var(--svg-color--c33c63, #C33C63);
}

.qbo0gacsu {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
}

.qhffjjblk {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.752 9.182c-.654 0-1.205.45-1.355 1.06a.273.273 0 0 0 .267.34h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.qixp4vm-i {
  d: path("M5.143 26.45c-.02-3.41 1.582-6.47 4-8.5v11.98l-3.98.02z");
}

.qk4xm-bhz {
  stop-color: var(--svg-color--f1863a, #F1863A);
}

.qmqo746eg {
  stop-color: var(--svg-color--e0ad88, #E0AD88);
}

.qn-z6_0fu {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
  stop-opacity: 0;
}

.qob7fubko {
  stop-color: var(--svg-color--d42045, #D42045);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r3gzp2rve {
  stop-color: var(--svg-color--ba4810, #BA4810);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.r9q9pn73s {
  stop-color: var(--svg-color--f19a2a, #F19A2A);
}

.rcf4twygv {
  d: path("M14.064 19.932c.824-.79 1.717-.938 2.058-.891c.133 1.793-.012 2.527-.723 3.309c-.424.466-1.054.722-1.51.843c-.203.054-.387-.108-.384-.318c.004-.362.011-.844.016-1.104c0-.628.02-1.308.543-1.84");
}

.rcioyubpk {
  stop-color: var(--svg-color--ca225e, #CA225E);
}

.rubvd1wqd {
  stop-color: var(--svg-color--bab5c0, #BAB5C0);
}

.rvnl-832d {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M8.312 25.267a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.s3pn0xbaq {
  d: path("M20.307 2.764c2.008.773 2.24 2.385 2.365 3.36c-3.464-.783-5.749-1.177-7.035-1.405c-.31-.055-.423-.42-.179-.617c1.12-.91 3.16-1.987 4.849-1.338");
}

.sk6ic1pcf {
  d: path("M11.318 13.612a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.236-3.76.324-5.642a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418H14.42c-1.846 0-3.342 1.512-3.342 3.379c0 1.86.117 3.69.239 5.556");
}

.smyxk1pmd {
  stop-color: var(--svg-color--e9dfee, #E9DFEE);
}

.sqj95vmrp {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M11.32 28.29a1.24 1.24 0 1 0 0-2.481a1.24 1.24 0 0 0 0 2.48");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t0v0swb7d {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.534 9.182c.653 0 1.204.45 1.355 1.06a.274.274 0 0 1-.268.34H17.39a.23.23 0 0 1-.227-.272c.125-.64.69-1.128 1.37-1.128");
}

.t12a8_qgv {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.77 8.038c.256-.184.897-.508 1.655-.38");
}

.t781mubvm {
  cx: 16.142px;
  cy: 17.041px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  rx: 3.844px;
  ry: 2.219px;
}

.ta7eky02w {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
  stop-opacity: 0;
}

.tfb2xgb0r {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M7.309 29.15a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.tm2bmw9uh {
  stop-color: var(--svg-color--4cc6ef, #4CC6EF);
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tx_tdxoal {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
  stop-opacity: 0;
}

.u-iovl2-y {
  d: path("m11.55 6.876l-.402.96c-.088.268-.06.654-.06 1.154a1.6 1.6 0 0 0-.537.177v-.475c0-.15 0-.313-.154-.776l-.04-.12c-.172-.51-.274-.811-.123-1.302z");
}

.u2vudgbww {
  stop-color: var(--svg-color--ffab34, #FFAB34);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.u8zhdtbla {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
}

.ub3fdabpz {
  fill: var(--svg-color--d5913d, #D5913D);
  d: path("m11.55 6.876l-.402.96c-.088.268-.06.654-.06 1.154a1.6 1.6 0 0 0-.537.177v-.475c0-.15 0-.313-.154-.776l-.04-.12c-.172-.51-.274-.811-.123-1.302z");
}

.ue4dcor2v {
  stop-color: var(--svg-color--c3aebd, #C3AEBD);
  stop-opacity: 0;
}

.ukhbhfbdb {
  stop-color: var(--svg-color--68faa7, #68FAA7);
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.v3wx_yddl {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vbxkmpbas {
  stop-color: var(--svg-color--cfcbd2, #CFCBD2);
}

.vksbihbpu {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M12.732 7.759a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.55a2.22 2.22 0 0 0-1.386.286a1 1 0 0 0-.092.06l-.003.001a.277.277 0 0 1-.34-.438z");
}

.vl4d3lbhw {
  stop-color: var(--svg-color--e66d36, #E66D36);
}

.vlpiorb9j {
  fill: var(--svg-color--b693a1, #B693A1);
  fill-rule: evenodd;
  d: path("M17.101 20.785c1.172-.437 1.967-1.288 1.967-2.268c0-1.424-1.683-2.578-3.759-2.578s-3.758 1.154-3.758 2.578c0 .98.795 1.831 1.967 2.268c-.389.436-.404.98-.404 1.486l-.014.924c-.002.176.152.311.323.266c.381-.1.909-.315 1.264-.706c.378-.415.565-.814.622-1.433c.058.62.245 1.018.622 1.433c.356.39.883.605 1.265.706c.17.045.324-.09.322-.266c-.003-.303-.01-.707-.013-.924c0-.505-.015-1.05-.404-1.486");
}

.vmv1-nbfg {
  d: path("M9.007 5.81c0-.45.344-.983.734-1.213c1.816-1.27 5.57-2.66 8.778-2.595c2.738.15 4.324 1.637 4.424 4.156c.019.491-.534.791-.934.791H10.264c-.685 0-1.257-.43-1.257-1.14");
}

.vn0ta5bom {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
}

.vnvkvjbds {
  stop-color: var(--svg-color--dd929a, #DD929A);
  stop-opacity: 0;
}

.vq38zyg1v {
  stop-color: var(--svg-color--c6a0e4, #C6A0E4);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.w_jg8bumh {
  stop-color: var(--svg-color--c01b54, #C01B54);
  stop-opacity: 0;
}

.wb9dsybrx {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.whnai1bce {
  d: path("M16.142 18.368c-1.05 0-1.908-.507-1.908-1.29v-2.693c0-1.109.858-2.017 1.908-2.017s1.91.908 1.91 2.017v2.692c0 .797-.86 1.291-1.91 1.291");
}

.wve9iuv6p {
  stop-color: var(--svg-color--e87c51, #E87C51);
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxo_vcdjw {
  stop-color: var(--svg-color--e3966a, #E3966A);
}

.xc8aunbib {
  stop-color: var(--svg-color--d7bedc, #D7BEDC);
}

.xcc0mcchc {
  stop-color: var(--svg-color--efa20d, #EFA20D);
}

.xctvn8crp {
  d: path("M7.383 29.08a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.xwbtobibq {
  stop-color: var(--svg-color--ffae37, #FFAE37);
}

.y_e8mrzhh {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
  stop-opacity: 0;
}

.y2f89vcbj {
  stop-color: var(--svg-color--ffc838, #FFC838);
}

.y3oq4nb4y {
  stop-color: var(--svg-color--97769c, #97769C);
}

.yan0zenen {
  stop-color: var(--svg-color--c02b72, #C02B72);
}

.yck9m-swa {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
  stop-opacity: 0;
}

.yz5elgb0p {
  d: path("M24.005 25.275c0-.401.325-.732.726-.732h2.77a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.97a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.z3dh2bb5s {
  d: path("M5.636 29.95h8.844l-2.031-5.852c-.602-1.805-2.022-3.296-4.61-2.977c-2.718.336-4.203 3.242-3.156 6.172z");
}

.z46muhatr {
  d: path("M8.383 25.19a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.z6d28bbdt {
  stop-color: var(--svg-color--e73a62, #E73A62);
  stop-opacity: 0;
}

.zae43h__y {
  d: path("M11.089 8.989a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zc_lsn8eo {
  d: path("M16.142 13.744c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.583.845c.665 0 1.249-.338 1.584-.846c.086-.129-.061-.278-.198-.209c-.4.21-.873.329-1.386.329");
}

.zxeleub3j {
  stop-color: var(--svg-color--3e9fe4, #3E9FE4);
}

</style>
