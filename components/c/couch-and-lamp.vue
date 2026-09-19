<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i2uUhab)" class="d0yb-yi4b"/><path fill="url(#i2gt7eP)" class="qkdohf5vh"/><path class="tx0rgebvu"/><path fill="url(#imnkHnb)" class="jblp3pvne"/><path fill="url(#i8NWNne)" class="jblp3pvne"/><path fill="url(#iTW2Ioc)" class="jblp3pvne"/><path fill="url(#ixym7ve)" class="jblp3pvne"/><path fill="url(#iIomjvd)" class="jblp3pvne"/><path class="rn631cnic"/><path fill="url(#iEAREdN)" class="xlsie9b4y"/><path fill="url(#ir1D5Ce)" class="xlsie9b4y"/><path fill="url(#inTAxDe)" class="xlsie9b4y"/><path fill="url(#i7jYbPo)" class="xlsie9b4y"/><path fill="url(#iGbEnoc)" class="xlsie9b4y"/><path fill="url(#iyc0cfL)" class="xlsie9b4y"/><path fill="url(#iAglgEg)" class="xlsie9b4y"/><g filter="url(#iuGvOzb)"><path class="tzu024aul"/><path fill="url(#iKBI1Wb)" class="oldch8b3r"/></g><g filter="url(#i43ejTc)"><path class="l_xtwg2cf"/></g><path stroke="url(#i5KQiKc)" class="nbac5m3za"/><g filter="url(#ikaMe0c)" class="yzbt72b_r"><path stroke="url(#idIapJO)" class="tjjih4baq"/><path stroke="url(#iLAhuGe)" class="tjjih4baq"/></g><g filter="url(#ivxfcYQ)"><path class="k7rojablc"/></g><g filter="url(#ifqsPgc)"><path fill="url(#iYBRFge)" class="hah22bcww"/><path fill="url(#ilkxUbp)" class="hah22bcww"/><path fill="url(#ignhBhe)" class="hah22bcww"/></g><path fill="url(#i8oiYEb)" class="phgsvcbsh"/><path fill="url(#iYvALie)" class="phgsvcbsh"/><path fill="url(#i7jePPV)" class="phgsvcbsh"/><path fill="url(#ibh6Ohb)" class="phgsvcbsh"/><g filter="url(#i8F5EWb)"><path stroke="url(#i7CbpQc)" class="rzo52ib_o"/></g><g filter="url(#ihGZ6id)"><path stroke="url(#iZTRhhc)" class="bll2a_bzu"/></g><g filter="url(#ioZXntc)"><path class="uv19vppbo"/></g><g filter="url(#igP7Xfc)"><path class="d2pa971jh"/></g><g filter="url(#ifc3Dra)"><path fill="url(#i4gxwPd)" class="gg_btlhuc"/></g><g filter="url(#iThlQid)"><path fill="url(#imxTU2d)" class="eu_z6-big"/></g><defs><linearGradient id="imnkHnb" x1="9.289" x2="9.289" y1="17.287" y2="19.146" gradientUnits="userSpaceOnUse"><stop offset=".032" class="i-6hy0blk"/><stop offset="1" class="w3o0bdhuq"/></linearGradient><linearGradient id="i8NWNne" x1="4.625" x2="6.5" y1="20.365" y2="20.365" gradientUnits="userSpaceOnUse"><stop class="v8bn643kf"/><stop offset="1" class="hw8175bxq"/></linearGradient><linearGradient id="iTW2Ioc" x1="7.25" x2="7.25" y1="24.896" y2="23.834" gradientUnits="userSpaceOnUse"><stop class="v8bn643kf"/><stop offset="1" class="giy41ybbr"/></linearGradient><linearGradient id="ixym7ve" x1="14.375" x2="12.531" y1="24.521" y2="24.521" gradientUnits="userSpaceOnUse"><stop class="hk6vgl84y"/><stop offset="1" class="ypzc2sble"/></linearGradient><linearGradient id="iIomjvd" x1="14.023" x2="13.508" y1="22.584" y2="22.584" gradientUnits="userSpaceOnUse"><stop class="lf34b73va"/><stop offset="1" class="ztoe5dbdj"/></linearGradient><linearGradient id="iEAREdN" x1="18.617" x2="18.617" y1="17.287" y2="19.146" gradientUnits="userSpaceOnUse"><stop offset=".032" class="i-6hy0blk"/><stop offset="1" class="w3o0bdhuq"/></linearGradient><linearGradient id="ir1D5Ce" x1="23.281" x2="21.406" y1="20.365" y2="20.365" gradientUnits="userSpaceOnUse"><stop class="v8bn643kf"/><stop offset="1" class="hw8175bxq"/></linearGradient><linearGradient id="inTAxDe" x1="20.656" x2="20.656" y1="24.896" y2="23.834" gradientUnits="userSpaceOnUse"><stop class="v8bn643kf"/><stop offset="1" class="giy41ybbr"/></linearGradient><linearGradient id="i7jYbPo" x1="13.531" x2="15.375" y1="24.521" y2="24.521" gradientUnits="userSpaceOnUse"><stop class="hk6vgl84y"/><stop offset="1" class="ypzc2sble"/></linearGradient><linearGradient id="iGbEnoc" x1="13.883" x2="14.398" y1="22.584" y2="22.584" gradientUnits="userSpaceOnUse"><stop class="lf34b73va"/><stop offset="1" class="ztoe5dbdj"/></linearGradient><linearGradient id="iyc0cfL" x1="23.281" x2="19.5" y1="26.084" y2="23.084" gradientUnits="userSpaceOnUse"><stop offset=".331" class="vinrj5bbv"/><stop offset="1" class="bfk3q0xfq"/></linearGradient><linearGradient id="iKBI1Wb" x1="13.934" x2="13.934" y1="24.639" y2="25.709" gradientUnits="userSpaceOnUse"><stop offset=".241" class="jmxj_iwae"/><stop offset="1" class="t1qs0qbac"/></linearGradient><linearGradient id="iLAhuGe" x1="27.922" x2="27.922" y1="27.74" y2="16.803" gradientUnits="userSpaceOnUse"><stop class="pdiq8zbmt"/><stop offset="1" class="o1s6n1b7b"/></linearGradient><linearGradient id="iYBRFge" x1="18.207" x2="24.912" y1="11.106" y2="11.106" gradientUnits="userSpaceOnUse"><stop offset=".253" class="shv6g7b_j"/><stop offset=".789" class="j665inb1v"/></linearGradient><linearGradient id="ilkxUbp" x1="23.406" x2="23.406" y1="13.318" y2="12.85" gradientUnits="userSpaceOnUse"><stop class="ymq4_5_ub"/><stop offset="1" class="s5ucmlb1e"/></linearGradient><linearGradient id="i7jePPV" x1="28.813" x2="28.813" y1="30.291" y2="29.928" gradientUnits="userSpaceOnUse"><stop class="xti7ukb8e"/><stop offset="1" class="o5a-7k78v"/></linearGradient><linearGradient id="i7CbpQc" x1="13.938" x2="6.659" y1="22.615" y2="22.749" gradientUnits="userSpaceOnUse"><stop class="d1d8pcbvn"/><stop offset="1" class="qe61elblm"/></linearGradient><linearGradient id="iZTRhhc" x1="22.758" x2="20.985" y1="18.099" y2="21.945" gradientUnits="userSpaceOnUse"><stop class="d1d8pcbvn"/><stop offset="1" class="qe61elblm"/></linearGradient><linearGradient id="i4gxwPd" x1="4.625" x2="4.625" y1="21.428" y2="27.709" gradientUnits="userSpaceOnUse"><stop class="kp9lekhkz"/><stop offset="1" class="t93e9bc7a"/></linearGradient><linearGradient id="imxTU2d" x1="24.102" x2="24.102" y1="21.428" y2="27.709" gradientUnits="userSpaceOnUse"><stop class="kp9lekhkz"/><stop offset="1" class="t93e9bc7a"/></linearGradient><filter id="iuGvOzb" width="19.32" height="5.094" x="3.773" y="24.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.32549 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25664"/></filter><filter id="i43ejTc" width="7.18" height="26.736" x="21.409" y="2.192" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.662745 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25664"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.521569 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_25664" result="effect2_innerShadow_18_25664"/></filter><filter id="ikaMe0c" width="6.963" height="26.836" x="21.409" y="2.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25664" stdDeviation=".15"/></filter><filter id="ivxfcYQ" width="4.406" height="9.414" x="2.438" y="19.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.380392 0 0 0 0 0.745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25664"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.305882 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_25664" result="effect2_innerShadow_18_25664"/></filter><filter id="ifqsPgc" width="7.484" height="7" x="18.375" y="6.318" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.560784 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25664"/></filter><filter id="i8F5EWb" width="8.594" height="7.797" x="5.219" y="17.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25664" stdDeviation=".25"/></filter><filter id="ihGZ6id" width="8.594" height="7.797" x="14.578" y="17.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25664" stdDeviation=".25"/></filter><filter id="ioZXntc" width="4.406" height="9.414" x="21.867" y="19.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.380392 0 0 0 0 0.745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25664"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.305882 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_25664" result="effect2_innerShadow_18_25664"/></filter><filter id="igP7Xfc" width="16.641" height="1.438" x="5.719" y="24.771" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25664" stdDeviation=".25"/></filter><filter id="ifc3Dra" width="2.563" height="8.188" x="3.344" y="20.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25664" stdDeviation=".375"/></filter><filter id="iThlQid" width="2.563" height="8.188" x="22.82" y="20.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25664" stdDeviation=".375"/></filter><radialGradient id="i2uUhab" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.50391 1.80188 0 24.016 30.29)" gradientUnits="userSpaceOnUse"><stop class="eyp39tnwp"/><stop offset="1" class="s9e7khi1d"/></radialGradient><radialGradient id="i2gt7eP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.50391 1.80188 0 5.078 30.29)" gradientUnits="userSpaceOnUse"><stop class="eyp39tnwp"/><stop offset="1" class="s9e7khi1d"/></radialGradient><radialGradient id="iAglgEg" cx="0" cy="0" r="1" gradientTransform="rotate(131.934 7.53 13.991)scale(1.23921 1.1939)" gradientUnits="userSpaceOnUse"><stop class="h6n-o5uhe"/><stop offset="1" class="ohi5ex0lm"/></radialGradient><radialGradient id="i5KQiKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7907 .46968 0 27.228 27.367)" gradientUnits="userSpaceOnUse"><stop class="yd_6nbbpg"/><stop offset="1" class="tnj6on5et"/></radialGradient><radialGradient id="idIapJO" cx="0" cy="0" r="1" gradientTransform="rotate(108.091 12.707 11.856)scale(6.31206 7.38492)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="pbkf01b0g"/><stop offset="1" class="fyqv44nap"/></radialGradient><radialGradient id="ignhBhe" cx="0" cy="0" r="1" gradientTransform="rotate(93.814 7.862 15.023)scale(2.34895 4.07743)" gradientUnits="userSpaceOnUse"><stop class="jc47e4bhg"/><stop offset="1" class="mypsjacsb"/></radialGradient><radialGradient id="i8oiYEb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.3125 0 0 -3.28621 29.844 29.584)" gradientUnits="userSpaceOnUse"><stop class="wc5q_ga6y"/><stop offset="1" class="zi180fbkb"/></radialGradient><radialGradient id="iYvALie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.0918 1.28125 0 29.297 30.068)" gradientUnits="userSpaceOnUse"><stop class="i0s9r2kex"/><stop offset="1" class="t_-fmob4t"/></radialGradient><radialGradient id="ibh6Ohb" cx="0" cy="0" r="1" gradientTransform="rotate(-164.204 16.484 12.98)scale(3.60895)" gradientUnits="userSpaceOnUse"><stop offset=".615" class="bdci92p9o"/><stop offset=".981" class="qs_c87urp"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:couch-and-lamp" /></template>
<style>
.bdci92p9o {
  stop-color: var(--svg-color--d2852c, #D2852C);
  stop-opacity: 0;
}

.bfk3q0xfq {
  stop-color: var(--svg-color--2a5aa1, #2A5AA1);
  stop-opacity: 0;
}

.bll2a_bzu {
  stroke-linecap: round;
  d: path("M15.578 18.38h6.344a.25.25 0 0 1 .25.25v5.548");
}

.d0yb-yi4b {
  d: path("M22.398 28.615h2.008v1.676h-2.008z");
}

.d1d8pcbvn {
  stop-color: var(--svg-color--5284c7, #5284C7);
}

.d2pa971jh {
  fill: var(--svg-color--4d83d2, #4D83D2);
  d: path("M6.219 25.271H21.86v.438H6.219z");
}

.eu_z6-big {
  d: path("M23.57 21.959a.531.531 0 0 1 1.063 0v6.156H23.57z");
}

.eyp39tnwp {
  stop-color: var(--svg-color--978bff, #978BFF);
}

.ft5dv1b6b {
  fill: none;
}

.fyqv44nap {
  stop-color: var(--svg-color--dddbde, #DDDBDE);
  stop-opacity: 0;
}

.gg_btlhuc {
  d: path("M4.094 21.959a.531.531 0 0 1 1.063 0v6.156H4.093z");
}

.giy41ybbr {
  stop-color: var(--svg-color--457bca, #457BCA);
  stop-opacity: 0;
}

.h6n-o5uhe {
  stop-color: var(--svg-color--5289c9, #5289C9);
}

.hah22bcww {
  d: path("M21.867 6.318a3.49 3.49 0 0 0-3.492 3.492v2.758c0 .415.336.75.75.75h5.484a.75.75 0 0 0 .75-.75V9.81a3.49 3.49 0 0 0-3.492-3.492");
}

.hk6vgl84y {
  stop-color: var(--svg-color--1859a4, #1859A4);
}

.hw8175bxq {
  stop-color: var(--svg-color--3261a8, #3261A8);
  stop-opacity: 0;
}

.i-6hy0blk {
  stop-color: var(--svg-color--3b77bb, #3B77BB);
}

.i0s9r2kex {
  stop-color: var(--svg-color--ffd96d, #FFD96D);
}

.j665inb1v {
  stop-color: var(--svg-color--ffdb4e, #FFDB4E);
}

.jblp3pvne {
  d: path("M4.625 18.537c0-.69.56-1.25 1.25-1.25h6.828c.69 0 1.25.56 1.25 1.25v6.734H4.625z");
}

.jc47e4bhg {
  stop-color: var(--svg-color--ffe96c, #FFE96C);
}

.jmxj_iwae {
  stop-color: var(--svg-color--397ac5, #397AC5);
}

.k7rojablc {
  fill: var(--svg-color--307ace, #307ACE);
  d: path("M2.438 22.271a1.703 1.703 0 1 1 3.406 0v5.961a1 1 0 0 1-1 1H3.437a1 1 0 0 1-1-1z");
}

.kp9lekhkz {
  stop-color: var(--svg-color--5c92db, #5C92DB);
}

.l_xtwg2cf {
  stroke: var(--svg-color--cbc9cc, #CBC9CC);
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M21.86 9.146V5.342a2.5 2.5 0 0 1 2.5-2.5h.98a2.5 2.5 0 0 1 2.5 2.5v23.586");
}

.lf34b73va {
  stop-color: var(--svg-color--022f89, #022F89);
}

.mypsjacsb {
  stop-color: var(--svg-color--ffd64c, #FFD64C);
  stop-opacity: 0;
}

.nbac5m3za {
  stroke-width: var(--svg-stroke-width--0-9px, 0.9px);
  d: path("M21.86 9.146V5.342a2.5 2.5 0 0 1 2.5-2.5h.98a2.5 2.5 0 0 1 2.5 2.5v23.586");
}

.o1s6n1b7b {
  stop-color: var(--svg-color--c5c0c3, #C5C0C3);
  stop-opacity: 0;
}

.o5a-7k78v {
  stop-color: var(--svg-color--e68945, #E68945);
  stop-opacity: 0;
}

.ohi5ex0lm {
  stop-color: var(--svg-color--5289c9, #5289C9);
  stop-opacity: 0;
}

.oldch8b3r {
  d: path("M4.773 24.639h18.32v3.593a1 1 0 0 1-1 1H5.774a1 1 0 0 1-1-1z");
}

.pbkf01b0g {
  stop-color: var(--svg-color--dddbde, #DDDBDE);
}

.pdiq8zbmt {
  stop-color: var(--svg-color--c5c0c3, #C5C0C3);
}

.phgsvcbsh {
  d: path("M25.349 29.783c-.058.275.172.508.453.508h4.119c.28 0 .51-.233.453-.508c-.255-1.213-1.297-2.121-2.515-2.121c-1.217 0-2.257.908-2.51 2.121");
}

.qe61elblm {
  stop-color: var(--svg-color--5284c7, #5284C7);
  stop-opacity: 0;
}

.qkdohf5vh {
  d: path("M3.461 28.615h2.008v1.676H3.461z");
}

.qs_c87urp {
  stop-color: var(--svg-color--884b45, #884B45);
}

.rn631cnic {
  fill: var(--svg-color--447ac9, #447AC9);
  d: path("M23.281 18.537c0-.69-.56-1.25-1.25-1.25h-6.828c-.69 0-1.25.56-1.25 1.25v6.734h9.328z");
}

.rzo52ib_o {
  stroke-linecap: round;
  d: path("M6.219 18.396h6.344a.25.25 0 0 1 .25.25v5.547");
}

.s5ucmlb1e {
  stop-color: var(--svg-color--eb9434, #EB9434);
  stop-opacity: 0;
}

.s9e7khi1d {
  stop-color: var(--svg-color--7f72ff, #7F72FF);
}

.shv6g7b_j {
  stop-color: var(--svg-color--f89b2f, #F89B2F);
}

.t_-fmob4t {
  stop-color: var(--svg-color--ffd96d, #FFD96D);
  stop-opacity: 0;
}

.t1qs0qbac {
  stop-color: var(--svg-color--397ac5, #397AC5);
  stop-opacity: 0;
}

.t93e9bc7a {
  stop-color: var(--svg-color--5487dd, #5487DD);
}

.tjjih4baq {
  d: path("M21.86 9.146V5.342c0-1.381 1.134-2.5 2.534-2.5h.994c1.4 0 2.534 1.119 2.534 2.5v23.586");
}

.tnj6on5et {
  stop-color: var(--svg-color--667295, #667295);
  stop-opacity: 0;
}

.tx0rgebvu {
  fill: var(--svg-color--447ac9, #447AC9);
  d: path("M4.625 18.537c0-.69.56-1.25 1.25-1.25h6.828c.69 0 1.25.56 1.25 1.25v6.734H4.625z");
}

.tzu024aul {
  fill: var(--svg-color--4a7ed9, #4A7ED9);
  d: path("M4.773 24.639h18.32v3.593a1 1 0 0 1-1 1H5.774a1 1 0 0 1-1-1z");
}

.uv19vppbo {
  fill: var(--svg-color--307ace, #307ACE);
  d: path("M21.867 22.271a1.703 1.703 0 1 1 3.406 0v5.961a1 1 0 0 1-1 1h-1.406a1 1 0 0 1-1-1z");
}

.v8bn643kf {
  stop-color: var(--svg-color--3261a8, #3261A8);
}

.vinrj5bbv {
  stop-color: var(--svg-color--163883, #163883);
}

.w3o0bdhuq {
  stop-color: var(--svg-color--3b77bb, #3B77BB);
  stop-opacity: 0;
}

.wc5q_ga6y {
  stop-color: var(--svg-color--ffe258, #FFE258);
}

.xlsie9b4y {
  d: path("M23.281 18.537c0-.69-.56-1.25-1.25-1.25h-6.828c-.69 0-1.25.56-1.25 1.25v6.734h9.328z");
}

.xti7ukb8e {
  stop-color: var(--svg-color--e68945, #E68945);
}

.yd_6nbbpg {
  stop-color: var(--svg-color--667295, #667295);
}

.ymq4_5_ub {
  stop-color: var(--svg-color--aa665b, #AA665B);
}

.ypzc2sble {
  stop-color: var(--svg-color--1859a4, #1859A4);
  stop-opacity: 0;
}

.yzbt72b_r {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
}

.zi180fbkb {
  stop-color: var(--svg-color--ffaf33, #FFAF33);
}

.ztoe5dbdj {
  stop-color: var(--svg-color--2a67b4, #2A67B4);
  stop-opacity: 0;
}

</style>
