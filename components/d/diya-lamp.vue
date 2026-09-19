<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i2loWlb)"><path class="hr247_baj"/><path fill="url(#iiolzBs)" class="niea7rikd"/><path fill="url(#iXBHqAd)" class="niea7rikd"/></g><g filter="url(#izSJ6nc)"><path fill="url(#i21H1Ce)" clip-rule="evenodd" class="i--3c8t2b"/></g><path fill="url(#i7lzcNb)" clip-rule="evenodd" class="i--3c8t2b"/><g filter="url(#isHEBEe)"><path class="thqo7db-g"/><path fill="url(#iMCmi7b)" class="f0l04bb3o"/><path fill="url(#in7vFUc)" class="f0l04bb3o"/></g><circle fill="url(#i2QV4Ne)" class="o8fetwlow"/><g filter="url(#iA8Diic)"><path fill="url(#irYI2jc)" class="daasiubwm"/></g><circle class="fa98zp64o"/><circle class="dycvzjprh"/><circle class="u8q8003tv"/><circle class="k-s49zbcm"/><circle class="hus5vokej"/><circle class="ewmnvugcy"/><circle class="rlqwb5mje"/><circle class="m1g6anbjh"/><circle class="tscakyvud"/><circle class="fbfq1r6_d"/><circle class="ijl8b_bsr"/><circle class="ccq3ksb1t"/><circle class="n1cxbmbeh"/><circle class="y5zrxxohe"/><circle class="ph5l4bb2x"/><circle class="eooqagxey"/><circle class="kms2szldt"/><circle class="zs_b3jkcv"/><circle class="zzt8-2btf"/><circle class="j88mf0n_e"/><g filter="url(#i9xiywd)" class="exlknac3d"><path class="xn0n1h7zs"/><path stroke="url(#iK1npnb)" class="np8fscc_o"/></g><g filter="url(#iWJlT2n)"><path fill="url(#i23MCTb)" class="pvw2f5j4l"/><path fill="url(#iqBdDZy)" class="pvw2f5j4l"/></g><circle fill="url(#iUnxpIe)" class="v5o96mb4f"/><defs><linearGradient id="iiolzBs" x1="27.681" x2="15.71" y1="17.262" y2="28.124" gradientUnits="userSpaceOnUse"><stop offset=".344" class="a4a5c6b-s"/><stop offset="1" class="ksav0wbik"/></linearGradient><linearGradient id="iXBHqAd" x1="1.235" x2="9.533" y1="21.108" y2="21.108" gradientUnits="userSpaceOnUse"><stop class="c4vh1y36m"/><stop offset="1" class="j6d5ngiij"/></linearGradient><linearGradient id="i21H1Ce" x1="10.512" x2="29.972" y1="14.53" y2="14.53" gradientUnits="userSpaceOnUse"><stop class="cq9p23brg"/><stop offset=".778" class="fe2bt8tis"/></linearGradient><linearGradient id="in7vFUc" x1="26.805" x2="18.102" y1="15.289" y2="15.289" gradientUnits="userSpaceOnUse"><stop class="am7f_btoq"/><stop offset="1" class="ap4h104zw"/></linearGradient><linearGradient id="irYI2jc" x1="21.559" x2="24.325" y1="16.04" y2="16.04" gradientUnits="userSpaceOnUse"><stop class="zqvjtss9n"/><stop offset="1" class="tpnqns2ba"/></linearGradient><linearGradient id="iK1npnb" x1="26.737" x2="26.062" y1="12.978" y2="14.563" gradientUnits="userSpaceOnUse"><stop class="gfv40sbfw"/><stop offset="1" class="yva3eebes"/></linearGradient><linearGradient id="i23MCTb" x1="26.667" x2="26.667" y1="6.227" y2="13.11" gradientUnits="userSpaceOnUse"><stop class="p92lizbmj"/><stop offset="1" class="x709p6p4h"/></linearGradient><filter id="i2loWlb" width="27.35" height="14.055" x="2.036" y="15.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.313726 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20590"/></filter><filter id="izSJ6nc" width="28.444" height="20.174" x="1.778" y="5.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.27451 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20590"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.596078 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20590" result="effect2_innerShadow_18_20590"/></filter><filter id="isHEBEe" width="23.319" height="15.924" x="4.028" y="7.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.435294 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20590"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.321569 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20590" result="effect2_innerShadow_18_20590"/></filter><filter id="iA8Diic" width="6.267" height="2.919" x="20.831" y="14.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20590" stdDeviation=".25"/></filter><filter id="i9xiywd" width="6.383" height="5.221" x="20.662" y="10.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.65" dy=".25"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.196078 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20590"/></filter><filter id="iWJlT2n" width="6.624" height="8.946" x="23.43" y="4.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.470588 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20590"/></filter><radialGradient id="i7lzcNb" cx="0" cy="0" r="1" gradientTransform="rotate(171.425 12.188 6.795)scale(4.29836 7.9749)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="skba94bzh"/><stop offset="1" class="x4ousbrmi"/></radialGradient><radialGradient id="iMCmi7b" cx="0" cy="0" r="1" gradientTransform="rotate(118.768 5.439 10.613)scale(3.73277 10.3847)" gradientUnits="userSpaceOnUse"><stop class="yf_if0ael"/><stop offset="1" class="odks135al"/></radialGradient><radialGradient id="i2QV4Ne" cx="0" cy="0" r="1" gradientTransform="rotate(130.544 4.827 9.292)scale(10.2398)" gradientUnits="userSpaceOnUse"><stop class="yezwgccps"/><stop offset="1" class="wdvu3-l8g"/></radialGradient><radialGradient id="iqBdDZy" cx="0" cy="0" r="1" gradientTransform="rotate(74.732 10.314 20.876)scale(7.38051 2.21278)" gradientUnits="userSpaceOnUse"><stop class="p5naeibyq"/><stop offset="1" class="o470rmbvc"/></radialGradient><radialGradient id="iUnxpIe" cx="0" cy="0" r="1" gradientTransform="rotate(115.908 11.106 13.069)scale(3.29006)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="g1ymvnp0g"/><stop offset="1" class="twoju7bkm"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:diya-lamp" /></template>
<style>
.a4a5c6b-s {
  stop-color: var(--svg-color--89515a, #89515A);
}

.am7f_btoq {
  stop-color: var(--svg-color--e16a1b, #E16A1B);
}

.ap4h104zw {
  stop-color: var(--svg-color--e16a1b, #E16A1B);
  stop-opacity: 0;
}

.c4vh1y36m {
  stop-color: var(--svg-color--79625b, #79625B);
}

.ccq3ksb1t {
  cx: 15.01px;
  cy: 23.46px;
  r: 0.506px;
  fill: var(--svg-color--40d187, #40D187);
}

.cq9p23brg {
  stop-color: var(--svg-color--ff7d48, #FF7D48);
}

.daasiubwm {
  d: path("m24.703 16.413l1.77-1.037a.25.25 0 0 0-.001-.433l-.75-.429c-.338.38-.831.62-1.38.62H21.98a.65.65 0 1 0 0 1.3h2.36q.184 0 .362-.02");
}

.dycvzjprh {
  cx: 13.344px;
  cy: 6.545px;
  r: 0.506px;
  fill: var(--svg-color--3dd181, #3DD181);
}

.eooqagxey {
  cx: 3.931px;
  cy: 19.141px;
  r: 0.506px;
  fill: var(--svg-color--34c77e, #34C77E);
}

.ewmnvugcy {
  cx: 25.131px;
  cy: 12.713px;
  r: 0.506px;
  fill: var(--svg-color--2c855a, #2C855A);
}

.exlknac3d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
}

.f0l04bb3o {
  d: path("m26.474 15.45l-10.03 5.875l-.106.06c-1.433.802-3.02 1.241-4.499 1.241c-4.031 0-7.31-3.278-7.31-7.337s3.279-7.337 7.31-7.337c1.683 0 3.497.568 5.06 1.58l.057.037l9.516 5.45a.25.25 0 0 1 .002.432");
}

.fa98zp64o {
  cx: 10.313px;
  cy: 6.545px;
  r: 0.506px;
  fill: var(--svg-color--ffd24d, #FFD24D);
}

.fbfq1r6_d {
  cx: 20.697px;
  cy: 20.28px;
  r: 0.506px;
  fill: var(--svg-color--3fd085, #3FD085);
}

.fe2bt8tis {
  stop-color: var(--svg-color--ff625f, #FF625F);
}

.ft5dv1b6b {
  fill: none;
}

.g1ymvnp0g {
  stop-color: var(--svg-color--ff8, #FF8);
}

.gfv40sbfw {
  stop-color: var(--svg-color--423332, #423332);
}

.hr247_baj {
  fill: var(--svg-color--692f59, #692F59);
  d: path("M5.298 26.397c-2.702-2.383-3.3-6.763-3.26-8.655v-2.299c.766 2.04 3.217 6.44 6.895 7.717s6.583.39 7.576-.211l12.079-7.271l.797.891c-2.29 2.314-7.371 7.442-10.355 10.238c-4.421 3.647-10.625 2.51-13.732-.41");
}

.hus5vokej {
  cx: 22.306px;
  cy: 11.069px;
  r: 0.506px;
  fill: var(--svg-color--df9742, #DF9742);
}

.i--3c8t2b {
  fill-rule: evenodd;
  d: path("M29.046 16.842a1.872 1.872 0 0 0-.016-3.24L18.258 7.434c-1.92-1.244-4.201-1.982-6.419-1.982c-5.418 0-9.81 4.404-9.81 9.837s4.392 9.837 9.81 9.837c1.063 0 2.141-.17 3.186-.483a12.6 12.6 0 0 0 2.53-1.074l.005-.003v.003zm-12.601 4.483l10.029-5.874a.25.25 0 0 0-.002-.433L16.956 9.57l-.058-.037c-1.562-1.012-3.376-1.58-5.059-1.58c-4.031 0-7.31 3.279-7.31 7.337c0 4.059 3.279 7.337 7.31 7.337c1.48 0 3.066-.439 4.499-1.241z");
}

.ijl8b_bsr {
  cx: 17.9px;
  cy: 21.928px;
  r: 0.506px;
  fill: var(--svg-color--ffd24e, #FFD24E);
}

.j6d5ngiij {
  stop-color: var(--svg-color--79625b, #79625B);
  stop-opacity: 0;
}

.j88mf0n_e {
  cx: 7.283px;
  cy: 7.68px;
  r: 0.506px;
  fill: var(--svg-color--3bd27e, #3BD27E);
}

.k-s49zbcm {
  cx: 19.439px;
  cy: 9.421px;
  r: 0.506px;
  fill: var(--svg-color--3ac07b, #3AC07B);
}

.kms2szldt {
  cx: 3.064px;
  cy: 16px;
  r: 0.506px;
  fill: var(--svg-color--ffd04b, #FFD04B);
}

.ksav0wbik {
  stop-color: var(--svg-color--89515a, #89515A);
  stop-opacity: 0;
}

.m1g6anbjh {
  cx: 26.447px;
  cy: 17.014px;
  r: 0.506px;
  fill: var(--svg-color--3fcd83, #3FCD83);
}

.n1cxbmbeh {
  cx: 11.838px;
  cy: 24.053px;
  r: 0.506px;
  fill: var(--svg-color--ffcf52, #FFCF52);
}

.niea7rikd {
  d: path("M5.298 26.397c-2.702-2.383-3.3-6.763-3.26-8.655v-2.299c.766 2.04 3.217 6.44 6.895 7.717s6.583.39 7.576-.211l12.079-7.271l.797.891c-2.29 2.314-7.371 7.442-10.355 10.238c-4.421 3.647-10.625 2.51-13.732-.41");
}

.np8fscc_o {
  d: path("M21.962 15.244h1.933a2.5 2.5 0 0 0 2.5-2.5v-1.17");
}

.o470rmbvc {
  stop-color: var(--svg-color--ff9e60, #FF9E60);
  stop-opacity: 0;
}

.o8fetwlow {
  cx: 11.595px;
  cy: 15.289px;
  r: 4.997px;
}

.odks135al {
  stop-color: var(--svg-color--ff9f5e, #FF9F5E);
  stop-opacity: 0;
}

.p5naeibyq {
  stop-color: var(--svg-color--ff9e60, #FF9E60);
}

.p92lizbmj {
  stop-color: var(--svg-color--ff7732, #FF7732);
}

.ph5l4bb2x {
  cx: 5.869px;
  cy: 21.73px;
  r: 0.506px;
  fill: var(--svg-color--ffce4e, #FFCE4E);
}

.pvw2f5j4l {
  d: path("m23.838 8.298l1.834-3.35c.45-.844 1.527-.847 1.972 0l1.822 3.297q.038.064.071.13l.007.012a3.237 3.237 0 1 1-5.706-.09");
}

.rlqwb5mje {
  cx: 27.791px;
  cy: 14.514px;
  r: 0.506px;
  fill: var(--svg-color--ffc84b, #FFC84B);
}

.skba94bzh {
  stop-color: var(--svg-color--d74344, #D74344);
}

.thqo7db-g {
  fill: var(--svg-color--ff914d, #FF914D);
  d: path("m26.474 15.45l-10.03 5.875l-.106.06c-1.433.802-3.02 1.241-4.499 1.241c-4.031 0-7.31-3.278-7.31-7.337s3.279-7.337 7.31-7.337c1.683 0 3.497.568 5.06 1.58l.057.037l9.516 5.45a.25.25 0 0 1 .002.432");
}

.tpnqns2ba {
  stop-color: var(--svg-color--e37048, #E37048);
  stop-opacity: 0;
}

.tscakyvud {
  cx: 23.572px;
  cy: 18.647px;
  r: 0.506px;
  fill: var(--svg-color--ffd150, #FFD150);
}

.twoju7bkm {
  stop-color: var(--svg-color--ff9d4f, #FF9D4F);
}

.u8q8003tv {
  cx: 16.572px;
  cy: 7.772px;
  r: 0.506px;
  fill: var(--svg-color--ffd24e, #FFD24E);
}

.v5o96mb4f {
  cx: 26.667px;
  cy: 9.996px;
  r: 1.753px;
}

.wdvu3-l8g {
  stop-color: var(--svg-color--ffcb4b, #FFCB4B);
}

.x4ousbrmi {
  stop-color: var(--svg-color--d74344, #D74344);
  stop-opacity: 0;
}

.x709p6p4h {
  stop-color: var(--svg-color--fc4275, #FC4275);
}

.xn0n1h7zs {
  stroke: var(--svg-color--5e2f64, #5E2F64);
  d: path("M21.962 15.244h1.933a2.5 2.5 0 0 0 2.5-2.5v-1.17");
}

.y5zrxxohe {
  cx: 8.666px;
  cy: 23.46px;
  r: 0.506px;
  fill: var(--svg-color--3bca85, #3BCA85);
}

.yezwgccps {
  stop-color: var(--svg-color--ffce4f, #FFCE4F);
}

.yf_if0ael {
  stop-color: var(--svg-color--ff9f5e, #FF9F5E);
}

.yva3eebes {
  stop-color: var(--svg-color--423332, #423332);
  stop-opacity: 0;
}

.zqvjtss9n {
  stop-color: var(--svg-color--e37048, #E37048);
}

.zs_b3jkcv {
  cx: 3.361px;
  cy: 12.75px;
  r: 0.506px;
  fill: var(--svg-color--36cc7c, #36CC7C);
}

.zzt8-2btf {
  cx: 4.845px;
  cy: 9.852px;
  r: 0.506px;
  fill: var(--svg-color--ffcf44, #FFCF44);
}

</style>
