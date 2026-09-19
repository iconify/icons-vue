<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iWuqHAd)" class="wdhmyzbtl"/><circle fill="url(#iPbbOBe)" class="ys34pmb0e"/><circle fill="url(#iw8PoLc)" class="xd1t-lbys"/><path fill="url(#id63g4b)" class="dfoeo21rd"/><g filter="url(#iqrgSqe)"><path fill="url(#i2Tk7nc)" class="y3m07ebtq"/></g><circle fill="url(#ioRVvYb)" transform="matrix(-1 0 0 1 21.001 4.933)" class="ix5z06j0s"/><circle fill="url(#iBoTtoV)" transform="matrix(-1 0 0 1 21.001 4.933)" class="ix5z06j0s"/><circle fill="url(#ircqhue)" transform="matrix(-1 0 0 1 26.001 6.933)" class="gxdceb8nt"/><circle fill="url(#i8wz4Xd)" transform="matrix(-1 0 0 1 26.001 6.933)" class="gxdceb8nt"/><g filter="url(#iCGSZfe)"><path fill="url(#iXZoUMd)" class="g-w_j3ihp"/></g><path fill="url(#iWD3eKe)" class="fdmnvxbyl"/><g filter="url(#ipb16ip)"><path class="liv2mnbhg"/></g><path fill="url(#iwUZ4bd)" class="s0ud_rb-h"/><path fill="url(#ihiT3TC)" class="lwf8mmb-z"/><path fill="url(#ioyPdtb)" stroke="url(#iszCd5c)" class="l9_akg5dh"/><g filter="url(#ibhPQwc)"><path stroke="url(#iPKNzje)" class="sjqm3nf7p"/></g><g filter="url(#i5lSUyy)"><path class="a6shqxbeu"/></g><g filter="url(#iWPOSub)"><path class="dywj6hv1u"/></g><path clip-rule="evenodd" class="pj37p7bbn"/><path class="as3fqccff"/><g filter="url(#iipEpDD)"><path fill="url(#iXpVU9v)" class="fm6664byp"/></g><path fill="url(#iGNuIec)" class="byx0h5bfa"/><g filter="url(#iu9sP2b)"><path fill="url(#itsk24d)" class="b2jwzgb6s"/></g><path class="afa7nkh5z"/><defs><radialGradient id="iWuqHAd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.00002 10.00004 -13.65734 -9.56013 9.001 1.933)" gradientUnits="userSpaceOnUse"><stop class="jxgr8u19g"/><stop offset=".365" class="ehcuc-lec"/><stop offset="1" class="e5rg9tb1g"/></radialGradient><radialGradient id="iPbbOBe" cx="0" cy="0" r="1" gradientTransform="matrix(-2 3.5 -3.5 -2 12.001 2.933)" gradientUnits="userSpaceOnUse"><stop class="bgd67i1tv"/><stop offset=".538" class="l2axf_12s"/></radialGradient><radialGradient id="iw8PoLc" cx="0" cy="0" r="1" gradientTransform="rotate(154.021 3.667 3.4)scale(4.75627)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="dwca-hb1z"/><stop offset="1" class="skyggtbgi"/></radialGradient><radialGradient id="id63g4b" cx="0" cy="0" r="1" gradientTransform="matrix(7.00002 10.00004 -13.65734 9.56013 23.001 1.933)" gradientUnits="userSpaceOnUse"><stop class="jxgr8u19g"/><stop offset=".365" class="ehcuc-lec"/><stop offset="1" class="e5rg9tb1g"/></radialGradient><radialGradient id="i2Tk7nc" cx="0" cy="0" r="1" gradientTransform="rotate(89.485 9.855 19.153)scale(3.8873 3.88729)" gradientUnits="userSpaceOnUse"><stop offset=".016" class="jjb2vub_p"/><stop offset=".832" class="l2axf_12s"/></radialGradient><radialGradient id="ioRVvYb" cx="0" cy="0" r="1" gradientTransform="matrix(7.54531 2.8766 -2.20974 5.79615 -.107 1.313)" gradientUnits="userSpaceOnUse"><stop offset=".016" class="jjb2vub_p"/><stop offset=".832" class="l2axf_12s"/></radialGradient><radialGradient id="iBoTtoV" cx="0" cy="0" r="1" gradientTransform="rotate(-156.613 3.134 .638)scale(3.97533 3.24907)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="r8fatvbas"/><stop offset="1" class="uonrembwq"/></radialGradient><radialGradient id="ircqhue" cx="0" cy="0" r="1" gradientTransform="rotate(154.021 3.389 2.318)scale(4.75627)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="dwca-hb1z"/><stop offset="1" class="skyggtbgi"/></radialGradient><radialGradient id="i8wz4Xd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.8476 -.18867 .1542 -4.7793 9.596 4.111)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="r8fatvbas"/><stop offset="1" class="uonrembwq"/></radialGradient><radialGradient id="iXZoUMd" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.583 10.532)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="y3bzghb5o"/><stop offset=".539" class="gb8_spbcj"/><stop offset="1" class="wtnr79bhr"/></radialGradient><radialGradient id="iWD3eKe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.24985 20.87504 -28.27335 -11.17367 17.878 11.244)" gradientUnits="userSpaceOnUse"><stop offset=".601" class="i-1ulaczm"/><stop offset="1" class="yjto57bgd"/></radialGradient><radialGradient id="iXpVU9v" cx="0" cy="0" r="1" gradientTransform="rotate(138.31 4.88 11.572)scale(3.80814 5.18257)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dkuql24df"/><stop offset="1" class="i-1ulaczm"/></radialGradient><filter id="iqrgSqe" width="7.176" height="6.055" x="24.069" y="9.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5251" stdDeviation=".25"/></filter><filter id="iCGSZfe" width="29.998" height="29.998" x="2.001" y=".933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-2"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.08 0"/><feBlend in2="shape" result="effect1_innerShadow_6815_5251"/></filter><filter id="ipb16ip" width="10.5" height="10.5" x="15.001" y="8.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5251" stdDeviation=".75"/></filter><filter id="ibhPQwc" width="10.187" height="7.923" x="14.751" y="20.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5251" stdDeviation=".25"/></filter><filter id="i5lSUyy" width="10.158" height="10.158" x="16.064" y="8.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5251" stdDeviation=".75"/></filter><filter id="iWPOSub" width="10.5" height="10.5" x="5.501" y="8.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5251" stdDeviation=".75"/></filter><filter id="iipEpDD" width="5.5" height="5.5" x="12.531" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5251" stdDeviation=".5"/></filter><filter id="iu9sP2b" width="4.003" height="4.003" x="14.281" y="14.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5251" stdDeviation=".5"/></filter><linearGradient id="iwUZ4bd" x1="24.001" x2="20.001" y1="7.933" y2="17.433" gradientUnits="userSpaceOnUse"><stop class="qkv45mbth"/><stop offset="1" class="w0tu1jbkj"/></linearGradient><linearGradient id="ihiT3TC" x1="12.001" x2="8.001" y1="7.933" y2="17.433" gradientUnits="userSpaceOnUse"><stop class="qkv45mbth"/><stop offset="1" class="w0tu1jbkj"/></linearGradient><linearGradient id="ioyPdtb" x1="16.001" x2="15.501" y1="22.433" y2="25.933" gradientUnits="userSpaceOnUse"><stop class="vnvw9sboa"/><stop offset="1" class="tbvrvj-rr"/></linearGradient><linearGradient id="iszCd5c" x1="5.878" x2="18.878" y1="23.308" y2="21.869" gradientUnits="userSpaceOnUse"><stop class="d_8fueide"/><stop offset="1" class="ot5rkb2ql"/></linearGradient><linearGradient id="iPKNzje" x1="23.688" x2="16.001" y1="17.431" y2="26.933" gradientUnits="userSpaceOnUse"><stop offset=".369" class="uzz4h95zv"/><stop offset="1" class="w_bm_rbge"/></linearGradient><linearGradient id="iGNuIec" x1="16.005" x2="16.005" y1="18.933" y2="15.434" gradientUnits="userSpaceOnUse"><stop class="yiq__d07e"/><stop offset=".444" class="emo973b4a"/><stop offset="1" class="uojyabbji"/></linearGradient><linearGradient id="itsk24d" x1="16.753" x2="15.715" y1="15.931" y2="16.734" gradientUnits="userSpaceOnUse"><stop offset=".369" class="g5dsuia7b"/><stop offset="1" class="agcaxrbjw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:clown-face" /></template>
<style>
.a6shqxbeu {
  fill: var(--svg-color--3450a6, #3450A6);
  d: path("M21.143 17.09a3.579 3.579 0 1 0 0-7.157a3.579 3.579 0 0 0 0 7.158");
}

.afa7nkh5z {
  fill: var(--svg-color--3e2930, #3E2930);
  d: path("M12.251 15.433a2.25 2.25 0 1 0 0-4.5a2.25 2.25 0 0 0 0 4.5");
}

.agcaxrbjw {
  stop-color: var(--svg-color--ff7bbc, #FF7BBC);
  stop-opacity: 0;
}

.as3fqccff {
  fill: var(--svg-color--3e2930, #3E2930);
  d: path("M19.751 15.433a2.25 2.25 0 1 0 0-4.5a2.25 2.25 0 0 0 0 4.5");
}

.b2jwzgb6s {
  d: path("M16.282 17.75a1.002 1.002 0 1 0 0-2.003a1.002 1.002 0 0 0 0 2.003");
}

.bgd67i1tv {
  stop-color: var(--svg-color--ff4a90, #FF4A90);
}

.byx0h5bfa {
  d: path("M16.001 18.933a1.75 1.75 0 1 0 0-3.5a1.75 1.75 0 0 0 0 3.5");
}

.d_8fueide {
  stop-color: var(--svg-color--e31f6a, #E31F6A);
}

.dfoeo21rd {
  d: path("M18.001 4.933a3 3 0 0 0 3.1 2.998a5.01 5.01 0 0 0 3.902 3.902l-.002.1a3 3 0 1 0 5.382-1.824a.61.61 0 0 1-.053-.673a5 5 0 0 0-6.832-6.832a.61.61 0 0 1-.673-.053a3 3 0 0 0-4.824 2.382");
}

.dkuql24df {
  stop-color: var(--svg-color--914bc7, #914BC7);
}

.dwca-hb1z {
  stop-color: var(--svg-color--ff508a, #FF508A);
}

.dywj6hv1u {
  fill: var(--svg-color--3450a6, #3450A6);
  d: path("M10.751 17.433a3.75 3.75 0 1 0 0-7.5a3.75 3.75 0 0 0 0 7.5");
}

.e5rg9tb1g {
  stop-color: var(--svg-color--d02651, #D02651);
}

.ehcuc-lec {
  stop-color: var(--svg-color--fc2e5f, #FC2E5F);
}

.emo973b4a {
  stop-color: var(--svg-color--ea0a4f, #EA0A4F);
}

.fdmnvxbyl {
  d: path("M16.016 30.93c9.335 0 13.999-6.267 13.999-13.998c0-7.732-4.664-14-13.999-14c-9.334 0-13.999 6.268-13.999 14c0 7.731 4.665 13.999 14 13.999");
}

.fm6664byp {
  d: path("M15.28 19.5a1.75 1.75 0 1 0 0-3.5a1.75 1.75 0 0 0 0 3.5");
}

.ft5dv1b6b {
  fill: none;
}

.g-w_j3ihp {
  d: path("M16 30.93c9.334 0 13.999-6.267 13.999-13.998c0-7.732-4.665-14-13.999-14S2.001 9.2 2.001 16.933c0 7.73 4.665 13.997 13.999 13.997");
}

.g5dsuia7b {
  stop-color: var(--svg-color--ff7bbc, #FF7BBC);
  stop-opacity: 0.72;
}

.gb8_spbcj {
  stop-color: var(--svg-color--d6b1d8, #D6B1D8);
}

.gxdceb8nt {
  r: 5px;
}

.i-1ulaczm {
  stop-color: var(--svg-color--cd8bff, #CD8BFF);
  stop-opacity: 0;
}

.ix5z06j0s {
  r: 3px;
}

.jjb2vub_p {
  stop-color: var(--svg-color--ff71a8, #FF71A8);
}

.jxgr8u19g {
  stop-color: var(--svg-color--ff478c, #FF478C);
}

.l2axf_12s {
  stop-color: var(--svg-color--ef3062, #EF3062);
}

.l9_akg5dh {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M23.781 19.933c0 4.24-3.54 6.75-7.78 6.75s-7.75-2.51-7.75-6.75c0 0 2.78 2 7.75 2c5.53-.01 7.78-2 7.78-2");
}

.liv2mnbhg {
  fill: var(--svg-color--8f74a1, #8F74A1);
  d: path("M20.251 17.433a3.75 3.75 0 1 0 0-7.5a3.75 3.75 0 0 0 0 7.5");
}

.lwf8mmb-z {
  d: path("M10.001 17.933a5 5 0 1 0 0-10a5 5 0 0 0 0 10");
}

.ot5rkb2ql {
  stop-color: var(--svg-color--f83594, #F83594);
}

.pj37p7bbn {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.001 13.183a3.75 3.75 0 1 1-7.5 0a3.75 3.75 0 0 1 7.5 0m9.5 0a3.75 3.75 0 1 1-7.5 0a3.75 3.75 0 0 1 7.5 0");
}

.qkv45mbth {
  stop-color: var(--svg-color--4095d9, #4095D9);
}

.r8fatvbas {
  stop-color: var(--svg-color--d62853, #D62853);
}

.s0ud_rb-h {
  d: path("M22.001 17.933a5 5 0 1 0 0-10a5 5 0 0 0 0 10");
}

.sjqm3nf7p {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.001 26.933c3.515 0 6.7-2.24 7.687-5.423");
}

.skyggtbgi {
  stop-color: var(--svg-color--ff4885, #FF4885);
  stop-opacity: 0;
}

.tbvrvj-rr {
  stop-color: var(--svg-color--eccedf, #ECCEDF);
}

.uojyabbji {
  stop-color: var(--svg-color--ec008c, #EC008C);
}

.uonrembwq {
  stop-color: var(--svg-color--d62853, #D62853);
  stop-opacity: 0;
}

.uzz4h95zv {
  stop-color: var(--svg-color--ff7bbc, #FF7BBC);
  stop-opacity: 0.4;
}

.vnvw9sboa {
  stop-color: var(--svg-color--c8a7c0, #C8A7C0);
}

.w_bm_rbge {
  stop-color: var(--svg-color--fb3982, #FB3982);
  stop-opacity: 0;
}

.w0tu1jbkj {
  stop-color: var(--svg-color--3e71c5, #3E71C5);
}

.wdhmyzbtl {
  d: path("M14.001 4.933a3 3 0 0 1-3.1 2.998A5.01 5.01 0 0 1 7 11.833q.003.05.002.1a3 3 0 1 1-5.382-1.824a.61.61 0 0 0 .053-.673a5 5 0 0 1 6.832-6.832a.61.61 0 0 0 .673-.053a3 3 0 0 1 4.824 2.382");
}

.wtnr79bhr {
  stop-color: var(--svg-color--c693ed, #C693ED);
}

.xd1t-lbys {
  cx: 6.001px;
  cy: 6.933px;
  r: 5px;
}

.y3bzghb5o {
  stop-color: var(--svg-color--f5f3f7, #F5F3F7);
}

.y3m07ebtq {
  d: path("M24.683 12.903a3 3 0 0 0 3.816 1.854a2.976 2.976 0 0 0 2.086-3.84c-.542-1.566-1.83-1.06-3.396-.518c-1.565.541-3.048.938-2.506 2.504");
}

.yiq__d07e {
  stop-color: var(--svg-color--e81123, #E81123);
}

.yjto57bgd {
  stop-color: var(--svg-color--c477ff, #C477FF);
}

.ys34pmb0e {
  cx: 11.001px;
  cy: 4.933px;
  r: 3px;
}

</style>
