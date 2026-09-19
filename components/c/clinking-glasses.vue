<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iR61Okd)" class="lh-7yyb_u"/><path fill="url(#isBXh2d)" class="lhkasxbmi"/><g filter="url(#iP08UFb)"><path class="ni_am77cd"/></g><path class="qkxobdbqm"/><path fill="url(#is7UHwe)" class="mne00-bbi"/><path fill="url(#ieSkZKb)" class="mne00-bbi"/><path fill="url(#iFAOqrG)" class="bt00dhn5i"/><path class="ds1vysqum"/><path fill="url(#iRpq2Ac)" class="v_l4xtxpz"/><path fill="url(#ifvEaue)" class="v_l4xtxpz"/><path fill="url(#iV8oKLd)" class="v_l4xtxpz"/><path fill="url(#iO7TDqe)" class="v_l4xtxpz"/><path class="uhy--jiiz"/><path fill="url(#iGklpqG)" class="pwzgcac-n"/><path fill="url(#i6MfYod)" class="pwzgcac-n"/><path fill="url(#iDnGpdJ)" class="pwzgcac-n"/><path fill="url(#iBnfBCd)" class="pwzgcac-n"/><path fill="url(#iTjdI5z)" class="lj2wf58ti"/><path fill="url(#iyECbGc)" class="w0cwrnb7j"/><g filter="url(#iv8qRvd)"><path class="um_oasbgl"/></g><path class="pjily2cpw"/><path fill="url(#isqd40c)" class="u0yw9-bbc"/><path fill="url(#iIDNXje)" class="u0yw9-bbc"/><path fill="url(#irJKeeb)" class="tvj0a4bxh"/><path fill="url(#iHYWg2d)" class="jtv15i4pm"/><path fill="url(#iV1m2ub)" class="fgikoeadb"/><path fill="url(#iJFEbsc)" class="fjlfb_4kl"/></g><defs><radialGradient id="ieSkZKb" cx="0" cy="0" r="1" gradientTransform="matrix(1.6875 -5.0625 10.12947 3.3765 11.499 19.562)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="yx_uyhg0i"/><stop offset=".381" class="rwanw8_lh"/><stop offset=".851" class="hg6mlvbmy"/></radialGradient><radialGradient id="iRpq2Ac" cx="0" cy="0" r="1" gradientTransform="rotate(70.017 -7.368 29.834)scale(.36577 2.94448)" gradientUnits="userSpaceOnUse"><stop class="dox_d6qrf"/><stop offset="1" class="r3k60abex"/></radialGradient><radialGradient id="ifvEaue" cx="0" cy="0" r="1" gradientTransform="matrix(.125 .375 -3.01875 1.00625 28 24.938)" gradientUnits="userSpaceOnUse"><stop class="dubb3bc5f"/><stop offset="1" class="r3k60abex"/></radialGradient><radialGradient id="iV8oKLd" cx="0" cy="0" r="1" gradientTransform="matrix(1.48499 .3125 -.67771 3.22045 21.14 26.688)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="ejau7cbxf"/><stop offset=".705" class="tky7fxb2p"/></radialGradient><radialGradient id="iO7TDqe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 -.09375 .20332 -3.5241 29.78 25.312)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="ejau7cbxf"/><stop offset=".705" class="tky7fxb2p"/></radialGradient><radialGradient id="iGklpqG" cx="0" cy="0" r="1" gradientTransform="matrix(-.10083 .3516 -2.83037 -.8117 5.07 27.355)" gradientUnits="userSpaceOnUse"><stop class="dox_d6qrf"/><stop offset="1" class="r3k60abex"/></radialGradient><radialGradient id="i6MfYod" cx="0" cy="0" r="1" gradientTransform="rotate(107.55 -5.614 18.067)scale(.39529 3.182)" gradientUnits="userSpaceOnUse"><stop class="dubb3bc5f"/><stop offset="1" class="r3k60abex"/></radialGradient><radialGradient id="iDnGpdJ" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 -.3125 .6777 2.71084 3.156 27.5)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="ejau7cbxf"/><stop offset=".705" class="tky7fxb2p"/></radialGradient><radialGradient id="iBnfBCd" cx="0" cy="0" r="1" gradientTransform="rotate(171.755 5.086 14.863)scale(2.39444 5.19275)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="ejau7cbxf"/><stop offset=".705" class="tky7fxb2p"/></radialGradient><radialGradient id="iIDNXje" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 -5.0625 8.7709 -.21656 22 17.938)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="yx_uyhg0i"/><stop offset=".514" class="rwanw8_lh"/><stop offset=".851" class="hg6mlvbmy"/></radialGradient><radialGradient id="irJKeeb" cx="0" cy="0" r="1" gradientTransform="rotate(180 9.117 2.48)scale(1.25964)" gradientUnits="userSpaceOnUse"><stop class="j1h0dwn5g"/><stop offset="1" class="mrhpprb5x"/></radialGradient><radialGradient id="iHYWg2d" cx="0" cy="0" r="1" gradientTransform="rotate(-99.383 13.176 -4.581)scale(1.28217 1.2822)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="u55b-0b0q"/><stop offset=".878" class="mrhpprb5x"/></radialGradient><radialGradient id="iV1m2ub" cx="0" cy="0" r="1" gradientTransform="rotate(180 9.903 2.48)scale(.50082)" gradientUnits="userSpaceOnUse"><stop class="c44qgwowv"/><stop offset="1" class="mrhpprb5x"/></radialGradient><linearGradient id="iR61Okd" x1="7.781" x2="9.354" y1="23.463" y2="23.985" gradientUnits="userSpaceOnUse"><stop offset=".03" class="caph6hbre"/><stop offset=".129" class="yagu4vbwl"/><stop offset=".18" class="y_5ijibka"/><stop offset=".389" class="j8dfmab1g"/><stop offset=".666" class="k4r89ib3h"/><stop offset=".92" class="y_5ijibka"/><stop offset="1" class="fsigvh0vk"/></linearGradient><linearGradient id="isBXh2d" x1="14.781" x2="10.031" y1="5.125" y2="19.594" gradientUnits="userSpaceOnUse"><stop class="ibkyb4b-m"/><stop offset=".042" class="vldkqvb_a"/><stop offset="1" class="trq-djb3b"/></linearGradient><linearGradient id="is7UHwe" x1="15.063" x2="8.138" y1="16.25" y2="13.938" gradientUnits="userSpaceOnUse"><stop offset=".098" class="d-iz7fbdo"/><stop offset=".225" class="h43-gsbct"/><stop offset=".36" class="y7db1xgbv"/><stop offset=".669" class="cnqxetbpn"/><stop offset=".896" class="ysmthrbpo"/></linearGradient><linearGradient id="iFAOqrG" x1="22.844" x2="24.484" y1="21.188" y2="20.641" gradientUnits="userSpaceOnUse"><stop offset=".03" class="caph6hbre"/><stop offset=".129" class="yagu4vbwl"/><stop offset=".18" class="y_5ijibka"/><stop offset=".531" class="j8dfmab1g"/><stop offset=".789" class="k4r89ib3h"/><stop offset=".92" class="y_5ijibka"/><stop offset="1" class="fsigvh0vk"/></linearGradient><linearGradient id="iTjdI5z" x1="14.357" x2="16.724" y1="14.521" y2="6.988" gradientUnits="userSpaceOnUse"><stop class="stui2mbih"/><stop offset=".761" class="vc--wpv5i"/></linearGradient><linearGradient id="iyECbGc" x1="18.313" x2="23.188" y1="2.625" y2="17.313" gradientUnits="userSpaceOnUse"><stop class="yebfb2svy"/><stop offset="1" class="un2sj93yz"/></linearGradient><linearGradient id="isqd40c" x1="24.656" x2="17.938" y1="10.906" y2="13.188" gradientUnits="userSpaceOnUse"><stop offset=".098" class="d-iz7fbdo"/><stop offset=".225" class="h43-gsbct"/><stop offset=".36" class="y7db1xgbv"/><stop offset=".669" class="cnqxetbpn"/><stop offset="1" class="buzycgbok"/></linearGradient><linearGradient id="iJFEbsc" x1="22.932" x2="20.272" y1="10.63" y2="3.195" gradientUnits="userSpaceOnUse"><stop class="stui2mbih"/><stop offset=".761" class="vc--wpv5i"/></linearGradient><filter id="iP08UFb" width="10.96" height="16.348" x="7.119" y="4.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31876" stdDeviation=".25"/></filter><filter id="iv8qRvd" width="11.107" height="16.445" x="14.251" y="1.771" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31876" stdDeviation=".25"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:clinking-glasses" /></template>
<style>
.bt00dhn5i {
  d: path("m25.875 24.851l-2.65-8.12l-1.62.53l2.65 8.12c-7.855 2.567 11.756-3.842 1.62-.53");
}

.buzycgbok {
  stop-color: var(--svg-color--ffc999, #FFC999);
}

.c44qgwowv {
  stop-color: var(--svg-color--ffeba6, #FFEBA6);
}

.caph6hbre {
  stop-color: var(--svg-color--c1e6ff, #C1E6FF);
}

.cnqxetbpn {
  stop-color: var(--svg-color--ffcb91, #FFCB91);
}

.d-iz7fbdo {
  stop-color: var(--svg-color--ffe4a5, #FFE4A5);
}

.dox_d6qrf {
  stop-color: var(--svg-color--d3f9ff, #D3F9FF);
}

.ds1vysqum {
  fill: var(--svg-color--c3f0ff, #C3F0FF);
  d: path("m28.415 24.021l-6.7 2.19a.82.82 0 0 0-.53 1.05c.14.44.61.68 1.05.53l6.69-2.18a.82.82 0 0 0 .53-1.05a.82.82 0 0 0-1.04-.54");
}

.dubb3bc5f {
  stop-color: var(--svg-color--cef8ff, #CEF8FF);
}

.ejau7cbxf {
  stop-color: var(--svg-color--bde1fc, #BDE1FC);
}

.fgikoeadb {
  d: path("M19.635 5.291a.33.33 0 1 0 0-.66a.33.33 0 0 0 0 .66");
}

.fjlfb_4kl {
  d: path("M22.734 10.547a.55.55 0 0 0 .332-.703l-2.202-6.43a.55.55 0 0 0-.703-.331a.55.55 0 0 0-.332.703l2.202 6.429a.55.55 0 0 0 .703.332");
}

.fsigvh0vk {
  stop-color: var(--svg-color--c7e5fe, #C7E5FE);
}

.ft5dv1b6b {
  fill: none;
}

.h43-gsbct {
  stop-color: var(--svg-color--ffefae, #FFEFAE);
}

.hg6mlvbmy {
  stop-color: var(--svg-color--ffcb9d, #FFCB9D);
  stop-opacity: 0;
}

.ibkyb4b-m {
  stop-color: var(--svg-color--c5f2ff, #C5F2FF);
}

.j1h0dwn5g {
  stop-color: var(--svg-color--ffdb8b, #FFDB8B);
}

.j8dfmab1g {
  stop-color: var(--svg-color--c3f0ff, #C3F0FF);
}

.jtv15i4pm {
  d: path("M19.635 7.671a.56.56 0 1 0 0-1.12a.56.56 0 0 0 0 1.12");
}

.k4r89ib3h {
  stop-color: var(--svg-color--cdf6ff, #CDF6FF);
}

.lh-7yyb_u {
  d: path("m6.625 27.021l2.65-8.12l1.62.53l-2.65 8.12c6.164 2.015-9.846-3.218-1.62-.53");
}

.lhkasxbmi {
  d: path("M9.855 19.851c1.96.64 4.07-.43 4.71-2.39l3.43-10.52a.66.66 0 0 0-.42-.83l-5.85-1.91a.66.66 0 0 0-.83.42l-3.43 10.52c-.64 1.96.43 4.07 2.39 4.71");
}

.lj2wf58ti {
  d: path("M14.25 14.336a.55.55 0 0 0 .689-.36l2.125-6.455a.55.55 0 0 0-.36-.69a.55.55 0 0 0-.69.36l-2.125 6.455a.55.55 0 0 0 .36.69");
}

.mne00-bbi {
  d: path("M10.205 18.791c1.57.51 3.26-.35 3.78-1.92l1.72-5.28a.546.546 0 0 0-.52-.71l-5.2.09c-.23 0-.43.15-.5.37l-1.2 3.67c-.51 1.57.35 3.26 1.92 3.78");
}

.mrhpprb5x {
  stop-color: var(--svg-color--fac77b, #FAC77B);
}

.ni_am77cd {
  fill: var(--svg-color--c2f0ff, #C2F0FF);
  d: path("M9.938 19.719c1.764.576 3.664-.419 4.24-2.183L17.55 7.029a.595.595 0 0 0-.378-.747l-5.267-1.72a.595.595 0 0 0-.747.379L7.786 15.447c-.576 1.765.387 3.696 2.152 4.272");
}

.pjily2cpw {
  fill: var(--svg-color--ffcb91, #FFCB91);
  d: path("M22.295 16.621c-1.57.51-3.26-.35-3.78-1.92l-2.3-7.07c-.21-.65.56-1.17 1.08-.73l.83.7c1.08.91 2.47 1.36 3.88 1.27c.53-.03 1.01.29 1.17.8l1.04 3.18c.51 1.56-.35 3.25-1.92 3.77");
}

.pwzgcac-n {
  d: path("m10.793 28.37l-6.708-2.165a.82.82 0 0 0-1.046.539a.82.82 0 0 0 .538 1.045l6.695 2.167a.82.82 0 0 0 1.045-.538a.82.82 0 0 0-.524-1.048");
}

.qkxobdbqm {
  fill: var(--svg-color--ffcb91, #FFCB91);
  d: path("M10.205 18.791c1.57.51 3.26-.35 3.78-1.92l1.72-5.28a.546.546 0 0 0-.52-.71l-5.2.09c-.23 0-.43.15-.5.37l-1.2 3.67c-.51 1.57.35 3.26 1.92 3.78");
}

.r3k60abex {
  stop-color: var(--svg-color--cdf9ff, #CDF9FF);
  stop-opacity: 0;
}

.rwanw8_lh {
  stop-color: var(--svg-color--ffcb9d, #FFCB9D);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.tky7fxb2p {
  stop-color: var(--svg-color--bde2fd, #BDE2FD);
  stop-opacity: 0;
}

.trq-djb3b {
  stop-color: var(--svg-color--bee9ff, #BEE9FF);
}

.tvj0a4bxh {
  d: path("M17.805 5.791a.83.83 0 1 0 0-1.66a.83.83 0 0 0 0 1.66");
}

.u0yw9-bbc {
  d: path("M22.295 16.621c-1.57.51-3.26-.35-3.78-1.92l-2.3-7.07c-.21-.65.56-1.17 1.08-.73l.83.7c1.08.91 2.47 1.36 3.88 1.27c.53-.03 1.01.29 1.17.8l1.04 3.18c.51 1.56-.35 3.25-1.92 3.77");
}

.u55b-0b0q {
  stop-color: var(--svg-color--ffea7e, #FFEA7E);
}

.uhy--jiiz {
  fill: var(--svg-color--c3f0ff, #C3F0FF);
  d: path("m10.793 28.37l-6.708-2.165a.82.82 0 0 0-1.046.539a.82.82 0 0 0 .538 1.045l6.695 2.167a.82.82 0 0 0 1.045-.538a.82.82 0 0 0-.524-1.048");
}

.um_oasbgl {
  fill: var(--svg-color--c8f2ff, #C8F2FF);
  d: path("M22.61 17.563c-1.766.576-3.844-.5-4.594-2.75l-3.208-9.936c-.152-.447 0-.69.453-.86l5.27-1.72c.316-.1.787.102.886.408l3.208 9.936c.703 2.28-.25 4.345-2.016 4.922");
}

.un2sj93yz {
  stop-color: var(--svg-color--beedff, #BEEDFF);
}

.v_l4xtxpz {
  d: path("m28.415 24.021l-6.7 2.19a.82.82 0 0 0-.53 1.05c.14.44.61.68 1.05.53l6.69-2.18a.82.82 0 0 0 .53-1.05a.82.82 0 0 0-1.04-.54");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vldkqvb_a {
  stop-color: var(--svg-color--c1dcf4, #C1DCF4);
}

.w0cwrnb7j {
  d: path("M22.645 17.681c-1.96.64-4.07-.43-4.71-2.39l-3.43-10.52c-.11-.35.08-.72.42-.83l5.85-1.91c.35-.11.72.08.83.42l3.43 10.52c.64 1.96-.43 4.07-2.39 4.71");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.y_5ijibka {
  stop-color: var(--svg-color--cef6ff, #CEF6FF);
}

.y7db1xgbv {
  stop-color: var(--svg-color--ffe6a7, #FFE6A7);
}

.yagu4vbwl {
  stop-color: var(--svg-color--ccf5ff, #CCF5FF);
}

.yebfb2svy {
  stop-color: var(--svg-color--bdddf6, #BDDDF6);
}

.ysmthrbpo {
  stop-color: var(--svg-color--ffe5a4, #FFE5A4);
}

.yx_uyhg0i {
  stop-color: var(--svg-color--ffbccc, #FFBCCC);
}

</style>
