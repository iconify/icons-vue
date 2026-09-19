<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#it6vBye)" class="oanp0ac-s"/><path fill="url(#iXCqehd)" class="oanp0ac-s"/><path fill="url(#ii785Nd)" class="oanp0ac-s"/><path fill="url(#i12TE5O)" class="oanp0ac-s"/><path fill="url(#iYc4bGb)" class="zxdlpbytt"/><path fill="url(#iOqoY3N)" class="zxdlpbytt"/><path fill="url(#iqJamHc)" class="zxdlpbytt"/><path fill="url(#izuAGEe)" class="fzk3p9bcx"/><path fill="url(#ia9Gqqc)" class="fzk3p9bcx"/><path fill="url(#im0McTM)" class="hvpjwfnho"/><path fill="url(#ifIEYld)" class="hvpjwfnho"/><path class="t0citubyq"/><path fill="url(#iCgt5ce)" class="nin--obrp"/><g filter="url(#i7c7APs)"><path class="s5a96_enq"/></g><path fill="url(#ivOaZJc)" class="me1m-5_yd"/><path fill="url(#iVG5sac)" class="me1m-5_yd"/><path fill="url(#iGr3WQd)" class="me1m-5_yd"/><path fill="url(#itCYcmd)" class="me1m-5_yd"/><path fill="url(#inZVBql)" class="me1m-5_yd"/><path fill="url(#i41fNBb)" class="rdadhsikt"/><path fill="url(#ixOEelc)" class="rdadhsikt"/><path fill="url(#it52Llb)" class="i8z8kzh2q"/><path fill="url(#icaXe1b)" class="i8z8kzh2q"/><path fill="url(#iehiyyY)" class="i8z8kzh2q"/><path fill="url(#itZOhkK)" class="wsz8a1b6d"/><path fill="url(#iFyZWue)" class="wsz8a1b6d"/><path fill="url(#iaxaCXc)" class="l1i2j_oyp"/><path fill="url(#iMs0gDb)" class="l1i2j_oyp"/><path fill="url(#ihJwvId)" class="osaznfbuo"/><path fill="url(#iwRCXDU)" class="osaznfbuo"/><path fill="url(#ijJk1cd)" class="ong07f93l"/><path fill="url(#iOJHuFd)" class="fen5c6bcp"/><path fill="url(#i9OjvRc)" class="m48z6949r"/><g filter="url(#iHrlimb)"><path stroke="url(#i7JbAAe)" class="euc4reb4e"/></g><g filter="url(#iWg64xb)"><ellipse fill="url(#iwYPwhb)" transform="rotate(43.661 26.081 14.36)" class="y6_hlqbzr"/></g><g filter="url(#i8uM0qb)"><path stroke="url(#izEeXnb)" class="hwjillbej"/></g><g filter="url(#iztfcod)"><path stroke="url(#icwVRJp)" class="bpr6omd_l"/></g><g filter="url(#i8du8fe)"><path stroke="url(#iwHMhBe)" class="z-cn-1bqz"/></g><g filter="url(#iyY3m5b)"><path fill="url(#iJd86ob)" clip-rule="evenodd" class="rqyefnb4m"/></g><g filter="url(#i3h2uQc)"><path stroke="url(#ih5eCPk)" class="lsi01vbrk"/></g><path fill="url(#iBUHTQc)" class="z69rbzbyj"/><path fill="url(#iEEIb3c)" class="z69rbzbyj"/><path fill="url(#ivkwDoZ)" class="qfb438d2k"/><path fill="url(#iinPL8c)" class="qfb438d2k"/><path fill="url(#iIhPoyd)" class="zgex4j6_b"/><path fill="url(#iTEKNhM)" class="zgex4j6_b"/><path fill="url(#iDqUsNf)" class="zgex4j6_b"/><path fill="url(#iwaYIcq)" class="zgex4j6_b"/></g><defs><linearGradient id="it6vBye" x1="22.484" x2="23.178" y1="19.86" y2="26.745" gradientUnits="userSpaceOnUse"><stop class="kqhej7b2s"/><stop offset="1" class="dvnuembil"/></linearGradient><linearGradient id="iXCqehd" x1="26.453" x2="23.391" y1="24.922" y2="24.922" gradientUnits="userSpaceOnUse"><stop offset=".173" class="s6ufqeblf"/><stop offset="1" class="e8ky8ywfo"/></linearGradient><linearGradient id="ii785Nd" x1="18.672" x2="21.516" y1="23.641" y2="24.24" gradientUnits="userSpaceOnUse"><stop offset=".173" class="s6ufqeblf"/><stop offset="1" class="e8ky8ywfo"/></linearGradient><linearGradient id="i12TE5O" x1="25.859" x2="23.547" y1="18.595" y2="23.297" gradientUnits="userSpaceOnUse"><stop offset=".173" class="s6ufqeblf"/><stop offset="1" class="e8ky8ywfo"/></linearGradient><linearGradient id="iYc4bGb" x1="17.357" x2="17.357" y1="20.895" y2="27.385" gradientUnits="userSpaceOnUse"><stop class="kqhej7b2s"/><stop offset="1" class="dvnuembil"/></linearGradient><linearGradient id="iOqoY3N" x1="11.172" x2="12.735" y1="21.547" y2="24.321" gradientUnits="userSpaceOnUse"><stop offset=".173" class="s6ufqeblf"/><stop offset="1" class="e8ky8ywfo"/></linearGradient><linearGradient id="iqJamHc" x1="13.422" x2="14.918" y1="24.891" y2="24.687" gradientUnits="userSpaceOnUse"><stop offset=".173" class="s6ufqeblf"/><stop offset="1" class="e8ky8ywfo"/></linearGradient><linearGradient id="izuAGEe" x1="19.61" x2="23.109" y1="29.579" y2="29.579" gradientUnits="userSpaceOnUse"><stop class="xpg7qbdiy"/><stop offset="1" class="u-1se5bme"/></linearGradient><linearGradient id="ia9Gqqc" x1="21.029" x2="20.992" y1="30.454" y2="29.361" gradientUnits="userSpaceOnUse"><stop class="v155f8htz"/><stop offset="1" class="bxkadub0v"/></linearGradient><linearGradient id="im0McTM" x1="16.453" x2="19.234" y1="28.885" y2="28.885" gradientUnits="userSpaceOnUse"><stop class="xpg7qbdiy"/><stop offset="1" class="u-1se5bme"/></linearGradient><linearGradient id="ifIEYld" x1="17.419" x2="17.373" y1="30.454" y2="29.362" gradientUnits="userSpaceOnUse"><stop class="v155f8htz"/><stop offset="1" class="bxkadub0v"/></linearGradient><linearGradient id="iCgt5ce" x1="24.266" x2="25.531" y1="11.814" y2="11.814" gradientUnits="userSpaceOnUse"><stop class="v3p2p5bvh"/><stop offset=".457" class="lczaz8bqx"/></linearGradient><linearGradient id="itCYcmd" x1="4.297" x2="6.047" y1="6.704" y2="8.454" gradientUnits="userSpaceOnUse"><stop class="i_w-ytbic"/><stop offset="1" class="yfd7hfbau"/></linearGradient><linearGradient id="inZVBql" x1="7.422" x2="7.703" y1="5.855" y2="7.11" gradientUnits="userSpaceOnUse"><stop offset=".257" class="i_w-ytbic"/><stop offset="1" class="yfd7hfbau"/></linearGradient><linearGradient id="ixOEelc" x1="10.148" x2="10.721" y1="8.17" y2="7.503" gradientUnits="userSpaceOnUse"><stop class="ojtnuacbn"/><stop offset=".751" class="zwnkbebbm"/></linearGradient><linearGradient id="it52Llb" x1="7.609" x2="9.141" y1="22.172" y2="18.266" gradientUnits="userSpaceOnUse"><stop class="vfp9xewyf"/><stop offset="1" class="u6-nu26qd"/></linearGradient><linearGradient id="iehiyyY" x1="11.312" x2="10.781" y1="20.453" y2="19.859" gradientUnits="userSpaceOnUse"><stop class="deir6ccmp"/><stop offset="1" class="fduumorjo"/></linearGradient><linearGradient id="itZOhkK" x1="8.734" x2="4.984" y1="15.385" y2="15.385" gradientUnits="userSpaceOnUse"><stop class="xspqbhqhs"/><stop offset="1" class="m_o19ewph"/></linearGradient><linearGradient id="iFyZWue" x1="6.78" x2="6.78" y1="21.282" y2="18.235" gradientUnits="userSpaceOnUse"><stop class="c_zsfrbve"/><stop offset="1" class="bf8nycbne"/></linearGradient><linearGradient id="iaxaCXc" x1="13.797" x2="10.047" y1="29.704" y2="29.704" gradientUnits="userSpaceOnUse"><stop class="u-1se5bme"/><stop offset="1" class="xpg7qbdiy"/></linearGradient><linearGradient id="iMs0gDb" x1="11.361" x2="11.304" y1="30.454" y2="29.363" gradientUnits="userSpaceOnUse"><stop class="v155f8htz"/><stop offset="1" class="bxkadub0v"/></linearGradient><linearGradient id="ihJwvId" x1="31.297" x2="28.859" y1="29.11" y2="29.11" gradientUnits="userSpaceOnUse"><stop class="u-1se5bme"/><stop offset="1" class="xpg7qbdiy"/></linearGradient><linearGradient id="iwRCXDU" x1="29.361" x2="29.304" y1="30.454" y2="29.363" gradientUnits="userSpaceOnUse"><stop class="v155f8htz"/><stop offset="1" class="bxkadub0v"/></linearGradient><linearGradient id="i9OjvRc" x1="18.122" x2="18.122" y1="18.885" y2="21.11" gradientUnits="userSpaceOnUse"><stop offset=".228" class="fpeij62ns"/><stop offset="1" class="c_zsfrbve"/></linearGradient><linearGradient id="i7JbAAe" x1="27.734" x2="27.734" y1="14.891" y2="29.266" gradientUnits="userSpaceOnUse"><stop class="dc8v_nkmm"/><stop offset=".406" class="rgo-oubqi"/><stop offset="1" class="hfnqa9b9m"/></linearGradient><linearGradient id="izEeXnb" x1="10.203" x2="14.422" y1="7.672" y2="15.36" gradientUnits="userSpaceOnUse"><stop class="cw1qesbgk"/><stop offset="1" class="rkte2e3gd"/></linearGradient><linearGradient id="icwVRJp" x1="12.599" x2="14.281" y1="19.608" y2="20.258" gradientUnits="userSpaceOnUse"><stop class="sww6c_mhw"/><stop offset="1" class="jo90e1bka"/></linearGradient><linearGradient id="iwHMhBe" x1="17.922" x2="14.819" y1="29.172" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="sww6c_mhw"/><stop offset="1" class="jo90e1bka"/></linearGradient><linearGradient id="iJd86ob" x1="23.066" x2="27.203" y1="22.641" y2="18.547" gradientUnits="userSpaceOnUse"><stop class="e6omxkb5r"/><stop offset="1" class="of17-8b7y"/></linearGradient><linearGradient id="ih5eCPk" x1="12.859" x2="10.836" y1="6.282" y2="5.486" gradientUnits="userSpaceOnUse"><stop class="cw1qesbgk"/><stop offset="1" class="rkte2e3gd"/></linearGradient><linearGradient id="iBUHTQc" x1="9.928" x2="9.928" y1="3.891" y2="1.885" gradientUnits="userSpaceOnUse"><stop class="xpg7qbdiy"/><stop offset="1" class="zbiv15bwz"/></linearGradient><linearGradient id="ivkwDoZ" x1="8.347" x2="8.347" y1="4.047" y2="1.885" gradientUnits="userSpaceOnUse"><stop class="xpg7qbdiy"/><stop offset="1" class="zbiv15bwz"/></linearGradient><linearGradient id="iIhPoyd" x1="9.656" x2="9.656" y1="6.047" y2="1.905" gradientUnits="userSpaceOnUse"><stop class="xpg7qbdiy"/><stop offset="1" class="zbiv15bwz"/></linearGradient><linearGradient id="iwaYIcq" x1="9.657" x2="9.657" y1="7.385" y2="5.735" gradientUnits="userSpaceOnUse"><stop class="prcj_e7zf"/><stop offset="1" class="u5y18db0i"/></linearGradient><radialGradient id="ivOaZJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 21.1924 -29.5 0 18.297 5.855)" gradientUnits="userSpaceOnUse"><stop class="a6z34eb7a"/><stop offset=".994" class="ucj_t49uq"/></radialGradient><radialGradient id="iVG5sac" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 -2.6875 2.59465 2.59465 22.453 21.829)" gradientUnits="userSpaceOnUse"><stop class="e6omxkb5r"/><stop offset="1" class="of17-8b7y"/></radialGradient><radialGradient id="iGr3WQd" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 -2.34375 3.68367 2.8487 25.36 23.954)" gradientUnits="userSpaceOnUse"><stop class="ic8r4eb-z"/><stop offset="1" class="u6-nu26qd"/></radialGradient><radialGradient id="i41fNBb" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 1.90625 -4.8612 .518 10.578 6.266)" gradientUnits="userSpaceOnUse"><stop offset=".453" class="u6-nu26qd"/><stop offset="1" class="vfp9xewyf"/></radialGradient><radialGradient id="icaXe1b" cx="0" cy="0" r="1" gradientTransform="matrix(3.6875 -6.4375 4.03565 2.31169 4.734 23.297)" gradientUnits="userSpaceOnUse"><stop class="e6omxkb5r"/><stop offset="1" class="of17-8b7y"/></radialGradient><radialGradient id="ijJk1cd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17969 0 0 -.61858 3.445 10.204)" gradientUnits="userSpaceOnUse"><stop class="em0_473iw"/><stop offset="1" class="ewdbrdbcp"/></radialGradient><radialGradient id="iOJHuFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.3306 .56337 -.4903 -.28772 6.253 9.242)" gradientUnits="userSpaceOnUse"><stop class="ckq7otbdc"/><stop offset="1" class="jx0oumbhp"/></radialGradient><radialGradient id="iwYPwhb" cx="0" cy="0" r="1" gradientTransform="rotate(91.339 6.97 19.297)scale(2.82843 3.86699)" gradientUnits="userSpaceOnUse"><stop class="sl-s4jibz"/><stop offset="1" class="rkte2e3gd"/></radialGradient><radialGradient id="iEEIb3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.62527 -.47936 0 11.042 2.182)" gradientUnits="userSpaceOnUse"><stop class="lao7lbbwj"/><stop offset="1" class="e0xqw8bag"/></radialGradient><radialGradient id="iinPL8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.70313 -.57674 0 9.148 2.196)" gradientUnits="userSpaceOnUse"><stop class="lao7lbbwj"/><stop offset="1" class="e0xqw8bag"/></radialGradient><radialGradient id="iTEKNhM" cx="0" cy="0" r="1" gradientTransform="rotate(153.346 7.048 2.675)scale(1.04897 .86483)" gradientUnits="userSpaceOnUse"><stop class="lao7lbbwj"/><stop offset="1" class="e0xqw8bag"/></radialGradient><radialGradient id="iDqUsNf" cx="0" cy="0" r="1" gradientTransform="matrix(-.85937 .67187 -.4208 -.53824 6.14 3.126)" gradientUnits="userSpaceOnUse"><stop class="lao7lbbwj"/><stop offset="1" class="e0xqw8bag"/></radialGradient><filter id="i7c7APs" width="2.13" height="4.239" x="24.455" y="8.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2649" stdDeviation=".2"/></filter><filter id="iHrlimb" width="7.359" height="16.734" x="23.781" y="11.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2649" stdDeviation=".625"/></filter><filter id="iWg64xb" width="5.283" height="5.234" x="23.439" y="11.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2649" stdDeviation=".5"/></filter><filter id="i8uM0qb" width="12.008" height="10.219" x="6.703" y="5.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2649" stdDeviation=".75"/></filter><filter id="iztfcod" width="2" height="6.844" x="11.422" y="18.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2649" stdDeviation=".375"/></filter><filter id="i8du8fe" width="2.769" height="6.238" x="15.241" y="21.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2649" stdDeviation=".25"/></filter><filter id="iyY3m5b" width="9.04" height="11.101" x="22.066" y="13.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2649" stdDeviation=".5"/></filter><filter id="i3h2uQc" width="3.797" height="1.844" x="9.344" y="5.782" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2649" stdDeviation=".15"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:deer" /></template>
<style>
.a6z34eb7a {
  stop-color: var(--svg-color--ffd299, #FFD299);
}

.bf8nycbne {
  stop-color: var(--svg-color--ce8493, #CE8493);
  stop-opacity: 0;
}

.bpr6omd_l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.422 19.532v4.844");
}

.bxkadub0v {
  stop-color: var(--svg-color--994987, #994987);
  stop-opacity: 0;
}

.c_zsfrbve {
  stop-color: var(--svg-color--ce8493, #CE8493);
}

.ckq7otbdc {
  stop-color: var(--svg-color--605255, #605255);
}

.cw1qesbgk {
  stop-color: var(--svg-color--ffe3b1, #FFE3B1);
}

.dc8v_nkmm {
  stop-color: var(--svg-color--feba83, #FEBA83);
  stop-opacity: 0;
}

.deir6ccmp {
  stop-color: var(--svg-color--e1975c, #E1975C);
}

.dvnuembil {
  stop-color: var(--svg-color--dd894d, #DD894D);
}

.e0xqw8bag {
  stop-color: var(--svg-color--9f5747, #9F5747);
  stop-opacity: 0;
}

.e6omxkb5r {
  stop-color: var(--svg-color--b76d4d, #B76D4D);
}

.e8ky8ywfo {
  stop-color: var(--svg-color--803a22, #803A22);
  stop-opacity: 0;
}

.em0_473iw {
  stop-color: var(--svg-color--4b3a3e, #4B3A3E);
}

.euc4reb4e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M25.406 13.032c.615.083 1.985.578 1.985 2.453v3.834c0 .86.37 1.68 1.015 2.25l.771.68a1 1 0 0 1 .339.75v3.517");
}

.ewdbrdbcp {
  stop-color: var(--svg-color--392034, #392034);
}

.fduumorjo {
  stop-color: var(--svg-color--e1975c, #E1975C);
  stop-opacity: 0;
}

.fen5c6bcp {
  d: path("M6.062 9.885a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.fpeij62ns {
  stop-color: var(--svg-color--facba0, #FACBA0);
}

.ft5dv1b6b {
  fill: none;
}

.fzk3p9bcx {
  d: path("m20.242 27.885l-.6 1.55c-.1.21.05.45.28.45h1.03c.3 0 .57-.14.75-.38l.93-1.62z");
}

.hfnqa9b9m {
  stop-color: var(--svg-color--f9b176, #F9B176);
  stop-opacity: 0;
}

.hvpjwfnho {
  d: path("M16.732 29.655c.04.17.21.22.38.22l1.4.01c.2 0 .27-.22.22-.38l-.43-1.62h-2.06z");
}

.hwjillbej {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m8.828 7.579l2.376 4.395a3 3 0 0 0 2.639 1.573h2.743");
}

.i_w-ytbic {
  stop-color: var(--svg-color--c5a078, #C5A078);
}

.i8z8kzh2q {
  d: path("m10.417 21.054l3.224-3.788l-5.22-5.375H5.156a.4.4 0 0 1 .258.373l.009 3.851c0 2.62 2.12 4.74 4.74 4.74h.01a.25.25 0 0 1 .245.2");
}

.ic8r4eb-z {
  stop-color: var(--svg-color--993984, #993984);
}

.jo90e1bka {
  stop-color: var(--svg-color--f1a976, #F1A976);
  stop-opacity: 0;
}

.jx0oumbhp {
  stop-color: var(--svg-color--3c273a, #3C273A);
}

.kqhej7b2s {
  stop-color: var(--svg-color--9f4c30, #9F4C30);
}

.l1i2j_oyp {
  d: path("M12.422 29.575v-1.69h-2v1.69c0 .17.14.31.31.31h1.38c.17 0 .31-.14.31-.31");
}

.lao7lbbwj {
  stop-color: var(--svg-color--9f5747, #9F5747);
}

.lczaz8bqx {
  stop-color: var(--svg-color--b97f52, #B97F52);
  stop-opacity: 0;
}

.lsi01vbrk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m9.844 7.126l.804-.103a4 4 0 0 0 1.265-.382l.728-.36");
}

.m_o19ewph {
  stop-color: var(--svg-color--d7b686, #D7B686);
}

.m48z6949r {
  d: path("M13.422 18.895v2h6.07c1.22 0 2.39-.51 3.23-1.39c.06-.07.1-.16.1-.25v-.01c0-.2-.16-.36-.36-.36h-9.04z");
}

.me1m-5_yd {
  d: path("m29.962 21.405l-1.27-1.27a.94.94 0 0 1-.27-.66v-3.87c0-2.07-1.68-3.75-3.75-3.75h-11.17c-.66 0-1.27-.38-1.57-.97l-1.463-2.668a.23.23 0 0 1 .203-.342c.98 0 1.84-.49 2.36-1.23a.505.505 0 0 0-.41-.79h-5.5c-.45 0-.88.18-1.19.49l-3.2 3.2c-.2.21-.31.48-.31.76c0 .86.7 1.56 1.56 1.56h1.03a.4.4 0 0 1 .4.399l.01 3.851c0 2.62 2.12 4.74 4.74 4.74h.01a.25.25 0 0 1 .25.25v8.45c0 .17.14.31.31.31h1.38c.17 0 .31-.14.31-.31v-3.42c0-.17.07-.32.18-.44c.52-.52.82-1.23.82-1.97v-2.84h6.07c1.27 0 2.49-.55 3.33-1.5c0 .94.46 1.83 1.22 2.38l4.11 2.94c.17.09.27.28.27.48v4.36c0 .17.14.31.31.31h1.37c.17 0 .31-.14.31-.31v-7.04c.01-.41-.15-.8-.45-1.1");
}

.nin--obrp {
  d: path("M26.422 13.205h-2v-4.02c0-.166.135-.302.299-.278c.96.146 1.7.98 1.7 1.978z");
}

.oanp0ac-s {
  d: path("M21.422 18.595v6.07c0 .15-.03.29-.1.42l-1.67 4.35c-.1.21.05.45.28.45h1.03c.3 0 .57-.14.75-.38l2.41-4.2c.19-.32.31-.6.31-.94v-5.77z");
}

.of17-8b7y {
  stop-color: var(--svg-color--b76d4d, #B76D4D);
  stop-opacity: 0;
}

.ojtnuacbn {
  stop-color: var(--svg-color--f0bc85, #F0BC85);
}

.ong07f93l {
  d: path("M3.422 10.885h.06c.64-.04.6-1-.04-1h-.92c-.07.14-.1.28-.1.44c0 .2.04.39.1.56z");
}

.osaznfbuo {
  d: path("M30.422 29.575v-1.69h-2v1.69c0 .17.14.31.31.31h1.37c.18 0 .32-.14.32-.31");
}

.prcj_e7zf {
  stop-color: var(--svg-color--552530, #552530);
}

.qfb438d2k {
  d: path("M8.922 1.885c-.28 0-.5.22-.5.5v1.16c0 .43-.31.79-.73.86l-.42.08c.13.13.25.26.37.4c.14.15.24.32.29.5c.87-.19 1.49-.95 1.49-1.84v-1.16c0-.28-.22-.5-.5-.5");
}

.rdadhsikt {
  d: path("M10.735 8.702L8.992 6.906c.694.057 2.858-.15 4.091-.737a.5.5 0 0 1-.051.476a2.88 2.88 0 0 1-2.36 1.23a.23.23 0 0 0-.203.342z");
}

.rgo-oubqi {
  stop-color: var(--svg-color--f9b176, #F9B176);
}

.rkte2e3gd {
  stop-color: var(--svg-color--fad99f, #FAD99F);
  stop-opacity: 0;
}

.rqyefnb4m {
  fill-rule: evenodd;
  d: path("M29.688 21.048L28.51 19.87a.87.87 0 0 1-.25-.612v-3.59c0-.404-.07-.792-.197-1.154h-4.997v4.66a2.74 2.74 0 0 0 1.131 2.208l3.122 2.233h2.786v-1.547c.01-.38-.139-.742-.417-1.02");
}

.s5a96_enq {
  stroke: var(--svg-color--fad99f, #FAD99F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.93 9.32c.396.058 1.18.446 1.18 1.509v1.78");
}

.s6ufqeblf {
  stop-color: var(--svg-color--803a22, #803A22);
}

.sl-s4jibz {
  stop-color: var(--svg-color--fad99f, #FAD99F);
}

.sww6c_mhw {
  stop-color: var(--svg-color--f1a976, #F1A976);
}

.t0citubyq {
  fill: var(--svg-color--e9a567, #E9A567);
  d: path("M26.422 13.205h-2v-4.02c0-.166.135-.302.299-.278c.96.146 1.7.98 1.7 1.978z");
}

.u-1se5bme {
  stop-color: var(--svg-color--9c634d, #9C634D);
}

.u5y18db0i {
  stop-color: var(--svg-color--552530, #552530);
  stop-opacity: 0;
}

.u6-nu26qd {
  stop-color: var(--svg-color--ab5a69, #AB5A69);
  stop-opacity: 0;
}

.ucj_t49uq {
  stop-color: var(--svg-color--c7773f, #C7773F);
}

.v155f8htz {
  stop-color: var(--svg-color--994987, #994987);
}

.v3p2p5bvh {
  stop-color: var(--svg-color--b97f52, #B97F52);
}

.vfp9xewyf {
  stop-color: var(--svg-color--ab5a99, #AB5A99);
}

.wsz8a1b6d {
  d: path("M6.875 19.532a3.02 3.02 0 0 0 1.547-2.637v-5.01H5.138a.4.4 0 0 1 .275.38l.009 3.85c0 1.343.557 2.555 1.453 3.417");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xpg7qbdiy {
  stop-color: var(--svg-color--63332a, #63332A);
}

.xspqbhqhs {
  stop-color: var(--svg-color--ffdea3, #FFDEA3);
}

.y6_hlqbzr {
  cx: 26.081px;
  cy: 14.361px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 1.872px;
  ry: 1.344px;
}

.yfd7hfbau {
  stop-color: var(--svg-color--c5a078, #C5A078);
  stop-opacity: 0;
}

.z-cn-1bqz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m15.89 22.297l1.47 4.938");
}

.z69rbzbyj {
  d: path("M8.932 5.225c-.24 0-.45-.17-.49-.42c-.05-.27.14-.52.41-.57l.84-.15a.87.87 0 0 0 .73-.86v-.84c0-.28.22-.5.5-.5s.5.22.5.5v.84c0 .92-.65 1.69-1.56 1.85l-.84.14c-.03.01-.06.01-.09.01");
}

.zbiv15bwz {
  stop-color: var(--svg-color--9d5749, #9D5749);
}

.zgex4j6_b {
  d: path("M13.922 1.905c-.28 0-.5.22-.5.5v.52c0 .31-.22.58-.53.63l-4.1.68c-.34.05-.64.21-.87.43c-.23-.23-.53-.41-.87-.48l-.58-.13a.75.75 0 0 1-.58-.73v.06c0-.28-.22-.5-.5-.5c-.27 0-.49.21-.5.47c.02.81.57 1.5 1.37 1.67l.58.13c.33.08.58.38.58.73v1c0 .28.22.5.5.5s.5-.22.5-.5v-1.04c0-.31.22-.58.53-.63l4.1-.68c.79-.13 1.37-.81 1.37-1.61v-.52c0-.28-.22-.5-.5-.5");
}

.zwnkbebbm {
  stop-color: var(--svg-color--f0bc85, #F0BC85);
  stop-opacity: 0;
}

.zxdlpbytt {
  d: path("M18.732 29.505c.04.17-.02.38-.22.38l-1.4-.01c-.17 0-.34-.05-.38-.22l-.87-3.14a.62.62 0 0 0-.29-.38c-.64-.37-1.11-.98-1.3-1.69l-.85-3.55h2.99z");
}

</style>
