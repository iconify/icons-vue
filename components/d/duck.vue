<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="djd2-7bml"/><path fill="url(#iH1RUne)" class="ra92p_p1r"/><path fill="url(#iMxFzdc)" class="ra92p_p1r"/><path fill="url(#ineuc8d)" class="ra92p_p1r"/><path fill="url(#iNj4FBk)" class="ra92p_p1r"/><path fill="url(#it4BOSc)" class="j1e3xdbdh"/><path fill="url(#impM26b)" class="j1e3xdbdh"/><g filter="url(#iUwW5wc)"><path fill="url(#iqIMGtc)" class="a7nm81rbh"/><path fill="url(#iLo5gKw)" class="a7nm81rbh"/><path fill="url(#it6Rxlc)" class="a7nm81rbh"/><path fill="url(#is0TVzc)" class="a7nm81rbh"/></g><path fill="url(#ioKXd0d)" class="x2abszbqt"/><path fill="url(#iuxBUpb)" class="x2abszbqt"/><path fill="url(#i2Vef9r)" class="x2abszbqt"/><path fill="url(#ixevkeb)" class="g99qrkbbc"/><path fill="url(#i56pdVc)" class="g99qrkbbc"/><path fill="url(#ifQQlTb)" class="g99qrkbbc"/><path fill="url(#iEohJuK)" class="dsokr2xkz"/><path fill="url(#i8cA4fe)" class="dsokr2xkz"/><path fill="url(#i3yMIRd)" class="dsokr2xkz"/><g filter="url(#iGxIEtb)"><path fill="url(#iocMEQb)" class="h19cjyt8b"/><path fill="url(#iSrS1Ce)" class="h19cjyt8b"/><path fill="url(#i1O0cec)" class="h19cjyt8b"/></g><g filter="url(#iGCWz0c)"><path fill="url(#iFNr3Fb)" class="u7uz2q7nk"/><path fill="url(#ieNuGAb)" class="u7uz2q7nk"/><path fill="url(#inlaT7c)" class="u7uz2q7nk"/><path fill="url(#iMKYMje)" class="u7uz2q7nk"/><path fill="url(#iMDGZQb)" class="u7uz2q7nk"/></g><path fill="url(#iSOReld)" class="u7uz2q7nk"/><g filter="url(#imVGqyd)"><path fill="url(#iYJ4Bfc)" class="nddai0x6p"/></g><defs><radialGradient id="iH1RUne" cx="0" cy="0" r="1" gradientTransform="rotate(126.978 6.3 5.523)scale(6.65001 7.19865)" gradientUnits="userSpaceOnUse"><stop class="zuurlmpcn"/><stop offset="1" class="v5dxlkb-b"/></radialGradient><radialGradient id="iMxFzdc" cx="0" cy="0" r="1" gradientTransform="rotate(-86.912 10.304 -1.065)scale(7.5422 6.93921)" gradientUnits="userSpaceOnUse"><stop offset=".868" class="v5dxlkb-b"/><stop offset="1" class="zuurlmpcn"/></radialGradient><radialGradient id="ineuc8d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50002 2.6875 -1.37533 -.76764 6.438 11.5)" gradientUnits="userSpaceOnUse"><stop class="l-cf4pb-n"/><stop offset="1" class="lpcb34bri"/></radialGradient><radialGradient id="iNj4FBk" cx="0" cy="0" r="1" gradientTransform="matrix(-6.0625 -.12498 .12792 -6.20515 18.625 9.313)" gradientUnits="userSpaceOnUse"><stop class="l-cf4pb-n"/><stop offset="1" class="lpcb34bri"/></radialGradient><radialGradient id="iqIMGtc" cx="0" cy="0" r="1" gradientTransform="matrix(5.8125 0 0 5.4375 3.781 7.625)" gradientUnits="userSpaceOnUse"><stop class="q-3gq3g2a"/><stop offset="1" class="d2g--2a-v"/></radialGradient><radialGradient id="is0TVzc" cx="0" cy="0" r="1" gradientTransform="matrix(6.1875 1.78125 -.7711 2.67853 2.5 6.437)" gradientUnits="userSpaceOnUse"><stop class="js8f2rbxq"/><stop offset="1" class="f0hl2hbgn"/></radialGradient><radialGradient id="ioKXd0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.50149 -.3622 10.586 6.355)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iuxBUpb" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 4.074 5.253)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="i56pdVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -6.375 0 16.5 23.063)" gradientUnits="userSpaceOnUse"><stop offset=".453" class="r_mk1-ajw"/><stop offset="1" class="u3x-gr9zu"/></radialGradient><radialGradient id="i8cA4fe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.875 0 0 -6.9375 31.438 19.125)" gradientUnits="userSpaceOnUse"><stop class="h6622gb-c"/><stop offset="0" class="biy93mebn"/><stop offset="1" class="wllrzotex"/></radialGradient><radialGradient id="i3yMIRd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 .625 -1.34658 4.98235 26.125 15.375)" gradientUnits="userSpaceOnUse"><stop class="h6622gb-c"/><stop offset="0" class="biy93mebn"/><stop offset=".884" class="wllrzotex"/></radialGradient><radialGradient id="iSrS1Ce" cx="0" cy="0" r="1" gradientTransform="rotate(-153.812 7.697 7.104)scale(2.12431 3.53998)" gradientUnits="userSpaceOnUse"><stop class="pqg5tg86v"/><stop offset="1" class="z177zy3sv"/></radialGradient><radialGradient id="i1O0cec" cx="0" cy="0" r="1" gradientTransform="rotate(-154.552 8.314 7.146)scale(2.50907 9.69633)" gradientUnits="userSpaceOnUse"><stop offset=".441" class="tysazwuls"/><stop offset="1" class="lomkn_3-r"/></radialGradient><radialGradient id="ieNuGAb" cx="0" cy="0" r="1" gradientTransform="matrix(16.62506 -14.2499 14.63588 17.07538 1.812 33.375)" gradientUnits="userSpaceOnUse"><stop class="qij8v3blx"/><stop offset=".735" class="ir_qqfbey"/></radialGradient><radialGradient id="inlaT7c" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 10.462 10.458)scale(26.7512 21.0614)" gradientUnits="userSpaceOnUse"><stop offset=".57" class="ir_qqfbey"/><stop offset="1" class="qij8v3blx"/></radialGradient><radialGradient id="iMKYMje" cx="0" cy="0" r="1" gradientTransform="rotate(116.787 9.825 15.05)scale(7.21137 7.21083)" gradientUnits="userSpaceOnUse"><stop class="nnblxgtza"/><stop offset="1" class="nwdu8cb5x"/></radialGradient><radialGradient id="iMDGZQb" cx="0" cy="0" r="1" gradientTransform="rotate(170.791 11.813 7.974)scale(10.8271 5.27601)" gradientUnits="userSpaceOnUse"><stop class="nnblxgtza"/><stop offset="1" class="nwdu8cb5x"/></radialGradient><radialGradient id="iSOReld" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 6.8125 -3.31972 -2.86288 28.375 12.625)" gradientUnits="userSpaceOnUse"><stop class="nnblxgtza"/><stop offset="1" class="nwdu8cb5x"/></radialGradient><linearGradient id="it4BOSc" x1="5.36" x2="11.5" y1="15" y2="15" gradientUnits="userSpaceOnUse"><stop class="szj0p_q_n"/><stop offset=".608" class="dug0v9blt"/><stop offset="1" class="crbfad6bo"/></linearGradient><linearGradient id="impM26b" x1="12.938" x2="11.188" y1="15.5" y2="15" gradientUnits="userSpaceOnUse"><stop class="szj0p_q_n"/><stop offset="1" class="y7ojn_ioh"/></linearGradient><linearGradient id="iLo5gKw" x1="4.594" x2="4.641" y1="10.516" y2="9.625" gradientUnits="userSpaceOnUse"><stop class="uqjy_7bpu"/><stop offset="1" class="hssmftbgj"/></linearGradient><linearGradient id="it6Rxlc" x1="7" x2="6.156" y1="2.969" y2="6.25" gradientUnits="userSpaceOnUse"><stop class="hle730b6v"/><stop offset="1" class="xwmbcob7n"/></linearGradient><linearGradient id="i2Vef9r" x1="10.339" x2="9.995" y1="6.123" y2="5.904" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="ixevkeb" x1="18.813" x2="18.813" y1="33.75" y2="27" gradientUnits="userSpaceOnUse"><stop offset=".255" class="rn6yynajv"/><stop offset="1" class="btdv_wd4q"/></linearGradient><linearGradient id="ifQQlTb" x1="15.688" x2="15.688" y1="32.938" y2="28.938" gradientUnits="userSpaceOnUse"><stop class="djtj5cb5i"/><stop offset="1" class="wet4d-nhl"/></linearGradient><linearGradient id="iEohJuK" x1="26.125" x2="28.063" y1="29.063" y2="16.875" gradientUnits="userSpaceOnUse"><stop class="lny9spxhe"/><stop offset="1" class="gikzv4bhv"/></linearGradient><linearGradient id="iocMEQb" x1="7.355" x2="7.353" y1="13.813" y2="33.52" gradientUnits="userSpaceOnUse"><stop class="ve5izccps"/><stop offset="1" class="lrsdolcxw"/></linearGradient><linearGradient id="iFNr3Fb" x1="27.375" x2="17.063" y1="13.25" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="g5ekmwb6e"/><stop offset="1" class="be1ko7b3d"/></linearGradient><linearGradient id="iYJ4Bfc" x1="11.484" x2="13.906" y1="11.375" y2="5.891" gradientUnits="userSpaceOnUse"><stop class="dx5wn8b4r"/><stop offset="1" class="wl6gk-bfb"/></linearGradient><filter id="iUwW5wc" width="5.05" height="6.47" x="2" y="3.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.15"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.804167 0 0 0 0 0.580149 0 0 0 0 0.281458 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4986"/></filter><filter id="iGxIEtb" width="8.96" height="14.75" x="3" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.325 0 0 0 0 0.214519 0 0 0 0 0.201771 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4986"/></filter><filter id="iGCWz0c" width="17.854" height="13.195" x="9.246" y="13.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592875 0 0 0 0 0.535503 0 0 0 0 0.645833 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4986"/></filter><filter id="imVGqyd" width="5.938" height="7.625" x="9.438" y="5.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4986" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:duck" /></template>
<style>
.a7nm81rbh {
  d: path("M7 3.68L4.79 6.15c-.5.54-1.21.85-1.95.85h-.33c-.28 0-.51.23-.51.51C2 8.88 3.12 10 4.49 10H7z");
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.be1ko7b3d {
  stop-color: var(--svg-color--cfc3dd, #CFC3DD);
}

.biy93mebn {
  stop-color: var(--svg-color--d8d4dd, #D8D4DD);
}

.btdv_wd4q {
  stop-color: var(--svg-color--bbaaca, #BBAACA);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.crbfad6bo {
  stop-color: var(--svg-color--e2d9eb, #E2D9EB);
}

.d2g--2a-v {
  stop-color: var(--svg-color--d2a776, #D2A776);
}

.djd2-7bml {
  fill: var(--svg-color--568831, #568831);
  d: path("M14.668 8.32A4.52 4.52 0 1 0 7 9.356V10c.269 0 .449.27.339.52l-3.81 8.63l5.38 2.2l5.76-13.03z");
}

.djtj5cb5i {
  stop-color: var(--svg-color--8e70a9, #8E70A9);
}

.dsokr2xkz {
  d: path("M27.43 13.57c-.01.01 0 .01 0 0c-.168.168-.344.309-.43.383V19c0 6.08-4.92 11-11 11h3c6.08 0 11-4.92 11-11v-4.36c0-1.34-1.62-2.01-2.57-1.07");
}

.dug0v9blt {
  stop-color: var(--svg-color--d9cfe3, #D9CFE3);
}

.dx5wn8b4r {
  stop-color: var(--svg-color--629440, #629440);
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.f0hl2hbgn {
  stop-color: var(--svg-color--ffda66, #FFDA66);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g5ekmwb6e {
  stop-color: var(--svg-color--ebe7f0, #EBE7F0);
}

.g99qrkbbc {
  d: path("M27.43 13.57c-.92.92-2.16 1.43-3.45 1.43H5.36C4.25 17.51 3 19.54 3 22c0 4.42 3.58 8 8 8h8c6.08 0 11-4.92 11-11v-4.36c0-1.34-1.62-2.01-2.57-1.07");
}

.gikzv4bhv {
  stop-color: var(--svg-color--f8f5fc, #F8F5FC);
}

.h19cjyt8b {
  d: path("M5.36 15C4.25 17.51 3 19.54 3 22c0 3.73 2.55 6.86 6 7.75V22.4c0-1.41.34-2.81.99-4.06L11.71 15z");
}

.h6622gb-c {
  stop-color: var(--svg-color--e7e4ea, #E7E4EA);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hle730b6v {
  stop-color: var(--svg-color--e3b651, #E3B651);
}

.hssmftbgj {
  stop-color: var(--svg-color--c9a37d, #C9A37D);
  stop-opacity: 0;
}

.ir_qqfbey {
  stop-color: var(--svg-color--988ba4, #988BA4);
  stop-opacity: 0;
}

.j1e3xdbdh {
  d: path("m11.719 15l.883-2H6.24l-.88 2z");
}

.js8f2rbxq {
  stop-color: var(--svg-color--ffda66, #FFDA66);
}

.l-cf4pb-n {
  stop-color: var(--svg-color--4c6634, #4C6634);
}

.lny9spxhe {
  stop-color: var(--svg-color--9883ad, #9883AD);
}

.lomkn_3-r {
  stop-color: var(--svg-color--533733, #533733);
  stop-opacity: 0;
}

.lpcb34bri {
  stop-color: var(--svg-color--4c6634, #4C6634);
  stop-opacity: 0;
}

.lrsdolcxw {
  stop-color: var(--svg-color--5b2a3f, #5B2A3F);
}

.nddai0x6p {
  d: path("m10.438 12.094l2.343-5.625h1.594l-2.317 5.625z");
}

.nnblxgtza {
  stop-color: var(--svg-color--f5f1fa, #F5F1FA);
}

.nwdu8cb5x {
  stop-color: var(--svg-color--f5f1fa, #F5F1FA);
  stop-opacity: 0;
}

.pqg5tg86v {
  stop-color: var(--svg-color--87645f, #87645F);
}

.q-3gq3g2a {
  stop-color: var(--svg-color--fac252, #FAC252);
}

.qij8v3blx {
  stop-color: var(--svg-color--988ba4, #988BA4);
}

.r_mk1-ajw {
  stop-color: var(--svg-color--a58cbe, #A58CBE);
}

.ra92p_p1r {
  d: path("M14.668 8.32A4.52 4.52 0 1 0 7 9.356V10c.269 0 .449.27.339.52l-3.81 8.63l5.38 2.2l5.76-13.03z");
}

.rn6yynajv {
  stop-color: var(--svg-color--997bb6, #997BB6);
}

.szj0p_q_n {
  stop-color: var(--svg-color--b0abae, #B0ABAE);
}

.tysazwuls {
  stop-color: var(--svg-color--533733, #533733);
}

.u3x-gr9zu {
  stop-color: var(--svg-color--a58cbe, #A58CBE);
  stop-opacity: 0;
}

.u7uz2q7nk {
  d: path("M26.997 13.955A4.87 4.87 0 0 1 23.98 15H11.71l-1.72 3.34q-.31.597-.525 1.232a4.13 4.13 0 0 0 .004 2.666C10.434 25.03 12.781 27 15.526 27h4.847c2.043 0 4.124-.718 5.149-2.485A10.96 10.96 0 0 0 27 19v-4.525z");
}

.uqjy_7bpu {
  stop-color: var(--svg-color--c9a37d, #C9A37D);
}

.v5dxlkb-b {
  stop-color: var(--svg-color--71a650, #71A650);
  stop-opacity: 0;
}

.ve5izccps {
  stop-color: var(--svg-color--794e49, #794E49);
}

.wet4d-nhl {
  stop-color: var(--svg-color--8e70a9, #8E70A9);
  stop-opacity: 0;
}

.wl6gk-bfb {
  stop-color: var(--svg-color--629440, #629440);
  stop-opacity: 0;
}

.wllrzotex {
  stop-color: var(--svg-color--d8d4dd, #D8D4DD);
  stop-opacity: 0;
}

.x2abszbqt {
  d: path("M10.438 7.016a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.xwmbcob7n {
  stop-color: var(--svg-color--e3b651, #E3B651);
  stop-opacity: 0;
}

.y7ojn_ioh {
  stop-color: var(--svg-color--b0abae, #B0ABAE);
  stop-opacity: 0;
}

.z177zy3sv {
  stop-color: var(--svg-color--87645f, #87645F);
  stop-opacity: 0;
}

.zuurlmpcn {
  stop-color: var(--svg-color--71a650, #71A650);
}

</style>
