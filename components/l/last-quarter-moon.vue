<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#i3qGz4o)" class="lmh4whbrs"/><circle fill="url(#iAgOlnd)" class="lmh4whbrs"/><circle fill="url(#i8ZPECo)" class="lmh4whbrs"/><circle fill="url(#iy0NQnc)" class="lmh4whbrs"/><g filter="url(#i69IkUd)"><circle stroke="url(#iGYVIkK)" class="t-a83-bcm"/></g><g filter="url(#icFtbRb)"><ellipse fill="url(#iRnHrOe)" class="s4-rzlb4x"/><ellipse fill="url(#iDl2zFb)" class="s4-rzlb4x"/><path stroke="url(#iwGJHid)" class="j5todu4pw"/></g><g filter="url(#ibRGnZv)"><path fill="url(#i14CPKc)" class="bq-g3x43q"/></g><g filter="url(#iqwR0Oe)"><path stroke="url(#iQfiiAe)" class="m5exnrbpk"/></g><path fill="url(#iUaVbmt)" class="v2p_6fzcd"/><circle fill="url(#iqfJvtw)" class="az0fwjbyp"/><g filter="url(#iHdpk7c)"><circle fill="url(#ihdA4bc)" class="g4k3q7cmw"/><circle stroke="url(#i2pnNjJ)" class="xrwbo5xlm"/></g><circle fill="url(#iuUWQbd)" class="h2-o4in6u"/><circle fill="url(#iNltv4c)" class="h2-o4in6u"/><circle fill="url(#iV5fxlb)" class="h2-o4in6u"/><path fill="url(#i1sbmye)" class="lf_xyqbww"/><g filter="url(#iEJsGMe)"><path stroke="url(#i1tUnmc)" class="mz88mlb1j"/></g><path fill="url(#iJIDgkc)" class="cmiujyb_i"/><path fill="url(#iSzvL0d)" class="cmiujyb_i"/><g filter="url(#ieW42Gd)"><path stroke="url(#iYKG1gg)" class="btcxgyrzu"/></g><g filter="url(#iefel2b)"><circle stroke="url(#iWmCMLb)" class="xk4y2_bhx"/></g><circle fill="url(#ighZGld)" class="az0fwjbyp"/><circle fill="url(#iYRnB8d)" class="az0fwjbyp"/><circle fill="url(#ilQvQDb)" class="az0fwjbyp"/><path fill="url(#iDSx0Vz)" class="lf_xyqbww"/><path fill="url(#iK72nye)" class="lf_xyqbww"/><path fill="url(#iM04xZr)" class="tvqmfc5ym"/><path fill="url(#izRUuKq)" class="tvqmfc5ym"/><path fill="url(#iS2RK2c)" class="tvqmfc5ym"/><path fill="url(#iIKYVUb)" class="tvqmfc5ym"/><g filter="url(#ifWWU2c)"><path stroke="url(#ilZwR6c)" class="g86qa-7-u"/></g><defs><radialGradient id="i3qGz4o" cx="0" cy="0" r="1" gradientTransform="rotate(130.574 5.911 8.893)scale(14.3174)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="kiew-vbiz"/><stop offset="1" class="mebb599ic"/></radialGradient><radialGradient id="iAgOlnd" cx="0" cy="0" r="1" gradientTransform="matrix(9.81246 3.1875 -5.7061 17.56575 1.51 12.812)" gradientUnits="userSpaceOnUse"><stop class="jw9cdr0hl"/><stop offset="1" class="u934xtbsl"/></radialGradient><radialGradient id="i8ZPECo" cx="0" cy="0" r="1" gradientTransform="matrix(-8.12486 15.37504 -21.28835 -11.24973 17.011 14.625)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="xmsh4x2fw"/><stop offset=".982" class="tm4xhebcg"/></radialGradient><radialGradient id="iy0NQnc" cx="0" cy="0" r="1" gradientTransform="matrix(0 17.7702 -20.4538 0 16 12.886)" gradientUnits="userSpaceOnUse"><stop offset=".889" class="mwr5e2beo"/><stop offset="1" class="h1_u8z46o"/></radialGradient><radialGradient id="iRnHrOe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.00536 0 0 -3.27072 16.745 5.214)" gradientUnits="userSpaceOnUse"><stop offset=".437" class="piy3tic3g"/><stop offset="1" class="r38asee8x"/></radialGradient><radialGradient id="iDl2zFb" cx="0" cy="0" r="1" gradientTransform="matrix(2.75536 0 0 2.97042 14.432 5.214)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="od4hrnb8k"/><stop offset="1" class="um7ihac7p"/></radialGradient><radialGradient id="i14CPKc" cx="0" cy="0" r="1" gradientTransform="matrix(-10.23981 15.57322 -15.85313 -10.42386 26.24 10.143)" gradientUnits="userSpaceOnUse"><stop class="wapsmeief"/><stop offset="1" class="ad8-9jxtc"/></radialGradient><radialGradient id="iUaVbmt" cx="0" cy="0" r="1" gradientTransform="matrix(1.07813 0 0 1.12965 15.933 5.214)" gradientUnits="userSpaceOnUse"><stop class="xy__gab6x"/><stop offset="1" class="su368lbmq"/></radialGradient><radialGradient id="ihdA4bc" cx="0" cy="0" r="1" gradientTransform="matrix(6.91643 -5.39316 1.77476 2.27603 20 13.396)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="wecidrbdj"/><stop offset="1" class="j9bg4_aho"/></radialGradient><radialGradient id="iuUWQbd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11395 4.03127 -7.29658 -3.82625 16.5 20.406)" gradientUnits="userSpaceOnUse"><stop class="nfbj00b7m"/><stop offset="1" class="x1bmjxb0i"/></radialGradient><radialGradient id="iNltv4c" cx="0" cy="0" r="1" gradientTransform="rotate(111.73 1.535 15.906)scale(3.90938 3.69613)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="u_0zt-b6m"/><stop offset="1" class="vadnxigha"/></radialGradient><radialGradient id="iV5fxlb" cx="0" cy="0" r="1" gradientTransform="rotate(-92.189 18.844 3.218)scale(3.17341 3.71969)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="l1829uhfc"/><stop offset="1" class="p6k-ex4aa"/></radialGradient><radialGradient id="iSzvL0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.0625 -4.28125 5.84388 -.08531 27.279 25.1)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="hyszpbcik"/><stop offset=".992" class="a6o3g7zqv"/></radialGradient><radialGradient id="ighZGld" cx="0" cy="0" r="1" gradientTransform="rotate(-46.392 21.192 -.673)scale(7.26522)" gradientUnits="userSpaceOnUse"><stop class="t8mzg_bgw"/><stop offset="1" class="asif75bjf"/></radialGradient><radialGradient id="iYRnB8d" cx="0" cy="0" r="1" gradientTransform="matrix(5.9375 -4.9375 3.68011 4.42545 6.636 14.625)" gradientUnits="userSpaceOnUse"><stop offset=".636" class="y2dt9rtuc"/><stop offset="1" class="tzxv8fgey"/></radialGradient><radialGradient id="ilQvQDb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.9485 1.56254 -1.61283 -5.1078 10.948 12)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="gn6-v4b1b"/><stop offset="1" class="legwfrc_m"/></radialGradient><radialGradient id="iK72nye" cx="0" cy="0" r="1" gradientTransform="rotate(-142.952 9.324 11.92)scale(5.57176 3.36972)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="te8heeq8v"/><stop offset="1" class="uu4-6olre"/></radialGradient><radialGradient id="iM04xZr" cx="0" cy="0" r="1" gradientTransform="rotate(-69.97 25.239 -.308)scale(4.02333 3.39651)" gradientUnits="userSpaceOnUse"><stop class="nmqja-b5r"/><stop offset="1" class="mf987ss-p"/></radialGradient><radialGradient id="izRUuKq" cx="0" cy="0" r="1" gradientTransform="matrix(2.11374 -4.27776 2.425 1.19825 16.402 23.641)" gradientUnits="userSpaceOnUse"><stop offset=".8" class="hcvo9rclz"/><stop offset="1" class="aouzsrgog"/></radialGradient><radialGradient id="iS2RK2c" cx="0" cy="0" r="1" gradientTransform="matrix(1.76863 2.48038 -2.52437 1.8 17.006 20.873)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="kowu5e5ac"/><stop offset="1" class="sk_-w8f9q"/></radialGradient><radialGradient id="iIKYVUb" cx="0" cy="0" r="1" gradientTransform="rotate(78.25 -4.634 20.394)scale(3.88692 3.67055)" gradientUnits="userSpaceOnUse"><stop offset=".649" class="xhmqgdkdw"/><stop offset="1" class="od20u6b3v"/></radialGradient><linearGradient id="iGYVIkK" x1="15.459" x2="15.459" y1="23.868" y2="18.433" gradientUnits="userSpaceOnUse"><stop class="m6upy3b_o"/><stop offset="1" class="tvgjt4bew"/></linearGradient><linearGradient id="iwGJHid" x1="17.188" x2="16.007" y1="4.884" y2="4.884" gradientUnits="userSpaceOnUse"><stop class="tneowg16w"/><stop offset="1" class="btjyt1bqw"/></linearGradient><linearGradient id="iQfiiAe" x1="17.273" x2="16.074" y1="5.114" y2="5.214" gradientUnits="userSpaceOnUse"><stop class="bfny-u51x"/><stop offset="1" class="g133hpb4p"/></linearGradient><linearGradient id="iqfJvtw" x1="11.833" x2="7.167" y1="10.167" y2="14.833" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="i2pnNjJ" x1="20.577" x2="23.646" y1="9" y2="14" gradientUnits="userSpaceOnUse"><stop class="co70-uzsf"/><stop offset=".492" class="ei1k3obco"/><stop offset="1" class="co70-uzsf"/></linearGradient><linearGradient id="i1sbmye" x1="11" x2="4" y1="24.5" y2="26" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="uyvx2tbpp"/></linearGradient><linearGradient id="i1tUnmc" x1="27.285" x2="24.178" y1="20.883" y2="26.253" gradientUnits="userSpaceOnUse"><stop class="z2mp41bxm"/><stop offset=".999" class="ot4-jgt4j"/></linearGradient><linearGradient id="iJIDgkc" x1="25.873" x2="27.06" y1="25.975" y2="19.787" gradientUnits="userSpaceOnUse"><stop class="g4rfypbmn"/><stop offset="1" class="o-kypwb8c"/></linearGradient><linearGradient id="iYKG1gg" x1="10.35" x2="5.287" y1="27.974" y2="23.506" gradientUnits="userSpaceOnUse"><stop class="t4vxokb_x"/><stop offset="1" class="n2qdeeb3x"/></linearGradient><linearGradient id="iWmCMLb" x1="11.325" x2="6.934" y1="9.361" y2="15.057" gradientUnits="userSpaceOnUse"><stop class="xe1h3_e7t"/><stop offset="1" class="nt99fmbml"/></linearGradient><linearGradient id="iDSx0Vz" x1="10.307" x2="5.964" y1="24.331" y2="26.993" gradientUnits="userSpaceOnUse"><stop class="zt28h012e"/><stop offset="1" class="bslbvcb-m"/></linearGradient><linearGradient id="ilZwR6c" x1="19" x2="15.335" y1="19.675" y2="21.427" gradientUnits="userSpaceOnUse"><stop class="v0xcpxbum"/><stop offset="1" class="l90x68blj"/></linearGradient><filter id="i69IkUd" width="5.6" height="5.6" x="13.7" y="18.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14027" stdDeviation=".1"/></filter><filter id="icFtbRb" width="4.148" height="3.7" x="13.389" y="3.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14027" stdDeviation=".1"/></filter><filter id="ibRGnZv" width="14.5" height="28.5" x="15.5" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.407843 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_14027"/></filter><filter id="iqwR0Oe" width="1.715" height="3.444" x="15.773" y="3.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14027" stdDeviation=".1"/></filter><filter id="iHdpk7c" width="5.8" height="5.8" x="19.6" y="8.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14027" stdDeviation=".1"/></filter><filter id="iEJsGMe" width="5.591" height="6.505" x="23.6" y="20.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14027" stdDeviation=".15"/></filter><filter id="ieW42Gd" width="6.717" height="6.224" x="4.583" y="22.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14027" stdDeviation=".1"/></filter><filter id="iefel2b" width="7.9" height="7.9" x="5.55" y="8.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14027" stdDeviation=".15"/></filter><filter id="ifWWU2c" width="3.75" height="5.75" x="15.625" y="18.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14027" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:last-quarter-moon" /></template>
<style>
.a6o3g7zqv {
  stop-color: var(--svg-color--663f8e, #663F8E);
}

.ad8-9jxtc {
  stop-color: var(--svg-color--6e409d, #6E409D);
}

.aouzsrgog {
  stop-color: var(--svg-color--64398c, #64398C);
}

.asif75bjf {
  stop-color: var(--svg-color--d5a04b, #D5A04B);
}

.az0fwjbyp {
  cx: 9.5px;
  cy: 12.5px;
  r: 3.5px;
}

.bfny-u51x {
  stop-color: var(--svg-color--744c9b, #744C9B);
}

.bq-g3x43q {
  d: path("M16 30V2c7.732 0 14 6.268 14 14s-6.268 14-14 14");
}

.bslbvcb-m {
  stop-color: var(--svg-color--ae6b71, #AE6B71);
}

.btcxgyrzu {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M10.269 28.602a13.67 13.67 0 0 1-5.36-4.346C5.549 23.443 6.469 23 7.585 23c1.933 0 3.327 1.724 3.415 3.424c0 .852-.225 1.57-.731 2.178Z");
}

.btjyt1bqw {
  stop-color: var(--svg-color--ffdd7b, #FFDD7B);
}

.cmiujyb_i {
  d: path("M28.955 21.316a14.04 14.04 0 0 1-4.073 5.507a3.5 3.5 0 0 1 4.074-5.507");
}

.co70-uzsf {
  stop-color: var(--svg-color--a57cd3, #A57CD3);
}

.ei1k3obco {
  stop-color: var(--svg-color--a57cd3, #A57CD3);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g133hpb4p {
  stop-color: var(--svg-color--744c9b, #744C9B);
  stop-opacity: 0;
}

.g4k3q7cmw {
  cx: 22.5px;
  cy: 11.5px;
  r: 2.5px;
}

.g4rfypbmn {
  stop-color: var(--svg-color--8a60b5, #8A60B5);
}

.g86qa-7-u {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16 23.95v-4.9q.243-.05.5-.05a2.5 2.5 0 0 1 .014 5h-.028a2.5 2.5 0 0 1-.486-.05Z");
}

.gn6-v4b1b {
  stop-color: var(--svg-color--ffca62, #FFCA62);
  stop-opacity: 0;
}

.h1_u8z46o {
  stop-color: var(--svg-color--c98394, #C98394);
}

.h2-o4in6u {
  cx: 16.5px;
  cy: 21.5px;
  r: 2.5px;
}

.hcvo9rclz {
  stop-color: var(--svg-color--64398c, #64398C);
  stop-opacity: 0;
}

.hyszpbcik {
  stop-color: var(--svg-color--663f8e, #663F8E);
  stop-opacity: 0;
}

.j5todu4pw {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.463 6.79c.984 0 1.8-.697 1.8-1.576s-.816-1.575-1.8-1.575c-.983 0-1.799.696-1.799 1.575c0 .88.816 1.575 1.8 1.575Z");
}

.j9bg4_aho {
  stop-color: var(--svg-color--8e61b7, #8E61B7);
}

.jw9cdr0hl {
  stop-color: var(--svg-color--b1884c, #B1884C);
}

.kiew-vbiz {
  stop-color: var(--svg-color--ffd366, #FFD366);
}

.kowu5e5ac {
  stop-color: var(--svg-color--664289, #664289);
  stop-opacity: 0;
}

.l1829uhfc {
  stop-color: var(--svg-color--e48f60, #E48F60);
  stop-opacity: 0;
}

.l90x68blj {
  stop-color: var(--svg-color--683b92, #683B92);
  stop-opacity: 0;
}

.legwfrc_m {
  stop-color: var(--svg-color--ffca62, #FFCA62);
}

.lf_xyqbww {
  d: path("M10.189 28.74a14.05 14.05 0 0 1-5.439-4.405a3.5 3.5 0 1 1 5.439 4.406");
}

.lmh4whbrs {
  cx: 16px;
  cy: 16px;
  r: 14px;
}

.m5exnrbpk {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16 6.64c.69-.196 1.188-.76 1.188-1.426S16.69 3.984 16 3.788");
}

.m6upy3b_o {
  stop-color: var(--svg-color--ffaf53, #FFAF53);
}

.mebb599ic {
  stop-color: var(--svg-color--e48d46, #E48D46);
}

.mf987ss-p {
  stop-color: var(--svg-color--6f4197, #6F4197);
}

.mwr5e2beo {
  stop-color: var(--svg-color--c98394, #C98394);
  stop-opacity: 0;
}

.mz88mlb1j {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M28.849 21.312A3.4 3.4 0 0 0 27.425 21C25.533 21 24 22.544 24 24.45c0 .878.326 1.68.863 2.289");
}

.n2qdeeb3x {
  stop-color: var(--svg-color--b96779, #B96779);
}

.nec_isxbo {
  stop-color: var(--svg-color--ffef71, #FFEF71);
}

.nfbj00b7m {
  stop-color: var(--svg-color--f8a065, #F8A065);
}

.nmqja-b5r {
  stop-color: var(--svg-color--724d94, #724D94);
}

.nt99fmbml {
  stop-color: var(--svg-color--d79c38, #D79C38);
}

.o-kypwb8c {
  stop-color: var(--svg-color--885bb3, #885BB3);
}

.od20u6b3v {
  stop-color: var(--svg-color--8b72a3, #8B72A3);
}

.od4hrnb8k {
  stop-color: var(--svg-color--cd9e56, #CD9E56);
  stop-opacity: 0;
}

.ot4-jgt4j {
  stop-color: var(--svg-color--7e55ac, #7E55AC);
}

.p6k-ex4aa {
  stop-color: var(--svg-color--e48f60, #E48F60);
}

.piy3tic3g {
  stop-color: var(--svg-color--f3bb63, #F3BB63);
}

.r38asee8x {
  stop-color: var(--svg-color--fff3a5, #FFF3A5);
}

.s334l8uyu {
  stop-color: var(--svg-color--f5c224, #F5C224);
}

.s4-rzlb4x {
  cx: 15.463px;
  cy: 5.214px;
  rx: 1.724px;
  ry: 1.5px;
}

.sk_-w8f9q {
  stop-color: var(--svg-color--664289, #664289);
}

.su368lbmq {
  stop-color: var(--svg-color--704e84, #704E84);
}

.t-a83-bcm {
  cx: 16.5px;
  cy: 21.5px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.t4vxokb_x {
  stop-color: var(--svg-color--b36558, #B36558);
}

.t8mzg_bgw {
  stop-color: var(--svg-color--f6b953, #F6B953);
}

.te8heeq8v {
  stop-color: var(--svg-color--af4c46, #AF4C46);
  stop-opacity: 0;
}

.tm4xhebcg {
  stop-color: var(--svg-color--c26965, #C26965);
}

.tneowg16w {
  stop-color: var(--svg-color--fdc36b, #FDC36B);
}

.tvgjt4bew {
  stop-color: var(--svg-color--ffaf53, #FFAF53);
  stop-opacity: 0;
}

.tvqmfc5ym {
  d: path("M16 23.95v-4.9q.243-.05.5-.05a2.5 2.5 0 0 1 .014 5h-.028a2.5 2.5 0 0 1-.486-.05");
}

.tzxv8fgey {
  stop-color: var(--svg-color--bd8d44, #BD8D44);
}

.u_0zt-b6m {
  stop-color: var(--svg-color--ffd87f, #FFD87F);
  stop-opacity: 0;
}

.u934xtbsl {
  stop-color: var(--svg-color--b1884c, #B1884C);
  stop-opacity: 0;
}

.um7ihac7p {
  stop-color: var(--svg-color--cd9e56, #CD9E56);
}

.uu4-6olre {
  stop-color: var(--svg-color--af4c46, #AF4C46);
}

.uyvx2tbpp {
  stop-color: var(--svg-color--fce35d, #FCE35D);
}

.v0xcpxbum {
  stop-color: var(--svg-color--683b92, #683B92);
}

.v2p_6fzcd {
  d: path("M16 6.64V3.788c.69.196 1.188.76 1.188 1.426S16.69 6.444 16 6.64");
}

.vadnxigha {
  stop-color: var(--svg-color--ffd87f, #FFD87F);
}

.wapsmeief {
  stop-color: var(--svg-color--a47bd1, #A47BD1);
}

.wecidrbdj {
  stop-color: var(--svg-color--b085d8, #B085D8);
}

.x1bmjxb0i {
  stop-color: var(--svg-color--ffbe6a, #FFBE6A);
}

.xe1h3_e7t {
  stop-color: var(--svg-color--e4ac50, #E4AC50);
}

.xhmqgdkdw {
  stop-color: var(--svg-color--8b72a3, #8B72A3);
  stop-opacity: 0;
}

.xk4y2_bhx {
  cx: 9.5px;
  cy: 12.5px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
}

.xmsh4x2fw {
  stop-color: var(--svg-color--c26965, #C26965);
  stop-opacity: 0;
}

.xrwbo5xlm {
  cx: 22.5px;
  cy: 11.5px;
  r: 2.6px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.xy__gab6x {
  stop-color: var(--svg-color--81589c, #81589C);
}

.y2dt9rtuc {
  stop-color: var(--svg-color--bd8d44, #BD8D44);
  stop-opacity: 0;
}

.z2mp41bxm {
  stop-color: var(--svg-color--7246a2, #7246A2);
}

.zt28h012e {
  stop-color: var(--svg-color--bd6152, #BD6152);
}

</style>
