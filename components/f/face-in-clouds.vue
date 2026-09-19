<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#i2P91bd)"><g filter="url(#igbmDvc)"><path fill="url(#iy3ub3b)" class="zannmacjr"/></g><path class="emmpbab-x"/><path fill="url(#iAQEgcs)" class="fr_40pbdn"/><path fill="url(#iAQEgcs)" class="j4u4wbcfb"/><circle fill="url(#igiJTmb)" class="v1avyhbkf"/><g filter="url(#ir04LYb)"><path clip-rule="evenodd" class="v6qe5cb6n"/></g><circle fill="url(#i256Hse)" class="ks92s1bjm"/><g filter="url(#iqJ6p8b)"><circle stroke="url(#ipzeeEe)" class="var8tmbqw"/></g><circle fill="url(#ivSIqvb)" class="kjqlqk9jw"/><g filter="url(#iFcmbLc)"><path clip-rule="evenodd" class="xmcpyxr8e"/></g><circle fill="url(#iO6uFkc)" class="h1dco9ega"/><circle fill="url(#i4jVwhe)" class="d3wn07b4a"/><g filter="url(#i9NyRde)"><circle stroke="url(#id2Cn3d)" class="f4p8rubns"/></g><circle fill="url(#iULrPPe)" class="n0vfpbcjv"/><circle fill="url(#iPlA8lX)" class="laoma2bub"/><circle fill="url(#ilqgn7b)" class="w6gnd3b1h"/><g filter="url(#isFFmIc)"><path clip-rule="evenodd" class="gk18xybwn"/></g><g filter="url(#ikiVXod)"><path clip-rule="evenodd" class="sqssu1bmm"/></g><circle fill="url(#ilMPuOb)" class="f4tf2mymo"/><circle stroke="url(#ixFiQRb)" class="r88_3k10l"/><g filter="url(#idNrWJd)"><circle stroke="url(#ixFiQRb)" class="po9h8hb5j"/></g><circle fill="url(#ihjkRCc)" class="z1spwobwt"/><circle fill="url(#iDKCA3b)" class="vqw_5qb-n"/><g filter="url(#iq8Qr3c)" class="nctb2ac4r"><circle class="v8vr1yqak"/></g><g filter="url(#iCtiFFe)" class="nctb2ac4r"><ellipse transform="rotate(-15 27.136 29.507)" class="kvnybqb9l"/></g><g filter="url(#i5rBUfb)"><ellipse class="mdby6obhr"/></g></g><defs><filter id="igbmDvc" width="29.998" height="29.998" x="2" y="0" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-2"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.08 0"/><feBlend in2="shape" result="effect1_innerShadow_30_40"/></filter><filter id="ir04LYb" width="13.021" height="9" x="24.114" y="18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_30_40" stdDeviation="1"/></filter><filter id="iqJ6p8b" width="14" height="14" x="25.5" y="12.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_30_40" stdDeviation=".75"/></filter><filter id="iFcmbLc" width="21" height="24" x="7" y="21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_30_40" stdDeviation="1"/></filter><filter id="i9NyRde" width="12" height="12" x="-5.5" y="14.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_30_40" stdDeviation=".25"/></filter><filter id="isFFmIc" width="6.5" height="11.387" x="9" y="-3.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_30_40" stdDeviation="1"/></filter><filter id="ikiVXod" width="12.781" height="9" x="24.904" y="4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_30_40" stdDeviation="1"/></filter><filter id="idNrWJd" width="20" height="20" x="26.5" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_30_40" stdDeviation=".75"/></filter><filter id="iq8Qr3c" width="12" height="12" x="-3" y="0" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_30_40" stdDeviation="1.5"/></filter><filter id="iCtiFFe" width="10.274" height="12.889" x="21.999" y="23.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_30_40" stdDeviation="1.5"/></filter><filter id="i5rBUfb" width="9" height="6" x="-4" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_30_40" stdDeviation="1"/></filter><radialGradient id="iy3ub3b" cx="0" cy="0" r="1" gradientTransform="rotate(123.93 6.854 9.426)scale(33.1436)" gradientUnits="userSpaceOnUse"><stop class="pnx4rebec"/><stop offset=".394" class="ajg27y5vv"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="igiJTmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8 -8 0 29 27)" gradientUnits="userSpaceOnUse"><stop class="o_p58hbtw"/><stop offset="1" class="i1-orb7ke"/></radialGradient><radialGradient id="ipzeeEe" cx="0" cy="0" r="1" gradientTransform="rotate(-56.31 36.456 -14.883)scale(4.66601)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="iO6uFkc" cx="0" cy="0" r="1" gradientTransform="matrix(-8 3 -3 -8 17.5 24)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="zu1-lrb6f"/><stop offset="1" class="lepfg0l8w"/></radialGradient><radialGradient id="id2Cn3d" cx="0" cy="0" r="1" gradientTransform="matrix(-3 -3 2.0999 -2.0999 5.5 23.5)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="iPlA8lX" cx="0" cy="0" r="1" gradientTransform="matrix(-3.99992 10.50003 -17.75364 -6.76313 30 2)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="qjx_0tbib"/><stop offset="1" class="qnrzvrb8o"/></radialGradient><radialGradient id="ilqgn7b" cx="0" cy="0" r="1" gradientTransform="matrix(9.49993 13 -13 9.49993 4 -1)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="w2ofxobzx"/><stop offset=".571" class="omd2k9cnw"/><stop offset=".82" class="x8o28pbmn"/></radialGradient><radialGradient id="ixFiQRb" cx="0" cy="0" r="1" gradientTransform="matrix(4 -6 6 4 30.5 18)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="ihjkRCc" cx="0" cy="0" r="1" gradientTransform="matrix(-8 8 -8 -8 25 -.5)" gradientUnits="userSpaceOnUse"><stop class="f73j7ybru"/><stop offset=".556" class="u8k7ndb0e"/><stop offset="1" class="xhfle5sqo"/></radialGradient><linearGradient id="iAQEgcs" x1="16.5" x2="15.5" y1="11" y2="18" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><linearGradient id="i256Hse" x1="32.5" x2="32.5" y1="14" y2="25" gradientUnits="userSpaceOnUse"><stop class="m8ysg7w-h"/><stop offset="1" class="qr96olcte"/></linearGradient><linearGradient id="ivSIqvb" x1="6" x2="6" y1="20" y2="36" gradientUnits="userSpaceOnUse"><stop class="rglpwqbaz"/><stop offset="1" class="k6ev-ubbh"/></linearGradient><linearGradient id="i4jVwhe" x1=".5" x2="-3" y1="16.179" y2="25.5" gradientUnits="userSpaceOnUse"><stop class="pp9yf1blx"/><stop offset="1" class="tv1ac5b3z"/></linearGradient><linearGradient id="iULrPPe" x1="26" x2="13" y1="30.5" y2="34" gradientUnits="userSpaceOnUse"><stop class="tqd0thb1b"/><stop offset="1" class="x470zsbyg"/></linearGradient><linearGradient id="ilMPuOb" x1="36.5" x2="36.5" y1="3" y2="20" gradientUnits="userSpaceOnUse"><stop class="u-l9_7bkh"/><stop offset="1" class="bu3ubedek"/></linearGradient><linearGradient id="iDKCA3b" x1="-2" x2="-2" y1="4.5" y2="17" gradientUnits="userSpaceOnUse"><stop class="pp9yf1blx"/><stop offset="1" class="tv1ac5b3z"/></linearGradient><clipPath id="i2P91bd"><path class="db87l3b0z"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:face-in-clouds" /></template>
<style>
.ajg27y5vv {
  stop-color: var(--svg-color--f48c50, #F48C50);
}

.bu3ubedek {
  stop-color: var(--svg-color--bda7d3, #BDA7D3);
}

.d3wn07b4a {
  cx: 0.5px;
  cy: 20.5px;
  r: 5.5px;
}

.db87l3b0z {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 4a4 4 0 0 1 4-4h24a4 4 0 0 1 4 4v24a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4z");
}

.ehgdi7b0u {
  stop-color: var(--svg-color--553b3e, #553B3E);
}

.emmpbab-x {
  fill: var(--svg-color--fff, #fff);
  d: path("M15 14.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m11 0a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0");
}

.f4p8rubns {
  cx: 0.5px;
  cy: 20.5px;
  r: 5.25px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.f4tf2mymo {
  cx: 36.5px;
  cy: 11.5px;
  r: 8.5px;
}

.f73j7ybru {
  stop-color: var(--svg-color--fffdff, #FFFDFF);
}

.fr_40pbdn {
  d: path("M11 18a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.ft5dv1b6b {
  fill: none;
}

.gk18xybwn {
  fill: var(--svg-color--9a7fa9, #9A7FA9);
  fill-rule: evenodd;
  d: path("M12.334 6.37A6.97 6.97 0 0 0 13.5 2.5a6.97 6.97 0 0 0-.947-3.518L11-.5c.667.5 1.9 2 1.5 4c-.264 1.319-.252 2.275-.166 2.87");
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.h1dco9ega {
  cx: 15.5px;
  cy: 25.5px;
  r: 4.5px;
}

.i1-orb7ke {
  stop-color: var(--svg-color--c3b7c1, #C3B7C1);
}

.j4u4wbcfb {
  d: path("M21 18a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.k6ev-ubbh {
  stop-color: var(--svg-color--d4c4e4, #D4C4E4);
}

.kiu9e17zs {
  stop-color: var(--svg-color--3d2432, #3D2432);
}

.kjqlqk9jw {
  cx: 6px;
  cy: 28px;
  r: 8px;
}

.ks92s1bjm {
  cx: 32.5px;
  cy: 19.5px;
  r: 5.5px;
}

.kvnybqb9l {
  cx: 27.136px;
  cy: 29.507px;
  fill: var(--svg-color--fff, #fff);
  rx: 2px;
  ry: 3.525px;
}

.laoma2bub {
  cx: 29px;
  cy: 4px;
  r: 7px;
}

.lepfg0l8w {
  stop-color: var(--svg-color--bba2d3, #BBA2D3);
}

.m8ysg7w-h {
  stop-color: var(--svg-color--bcb1c1, #BCB1C1);
}

.mdby6obhr {
  cx: 0.5px;
  cy: 26px;
  fill: var(--svg-color--ac84d3, #AC84D3);
  rx: 2.5px;
  ry: 1px;
}

.n0vfpbcjv {
  cx: 19.5px;
  cy: 32.5px;
  r: 8.5px;
}

.nctb2ac4r {
  opacity: var(--svg-opacity--0-8, 0.8);
}

.o_p58hbtw {
  stop-color: var(--svg-color--f4ecfd, #F4ECFD);
}

.omd2k9cnw {
  stop-color: var(--svg-color--d4c3e1, #D4C3E1);
}

.pnx4rebec {
  stop-color: var(--svg-color--f8a940, #F8A940);
}

.po9h8hb5j {
  cx: 36.5px;
  cy: 11.5px;
  r: 8.25px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.pp9yf1blx {
  stop-color: var(--svg-color--fcfbfd, #FCFBFD);
}

.qjx_0tbib {
  stop-color: var(--svg-color--f4effb, #F4EFFB);
}

.qnrzvrb8o {
  stop-color: var(--svg-color--b499c0, #B499C0);
}

.qr96olcte {
  stop-color: var(--svg-color--c8b3df, #C8B3DF);
}

.r88_3k10l {
  cx: 36.5px;
  cy: 11.5px;
  r: 8.375px;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  opacity: var(--svg-opacity--0-08, 0.08);
}

.rglpwqbaz {
  stop-color: var(--svg-color--f0e2f0, #F0E2F0);
}

.sqssu1bmm {
  fill: var(--svg-color--baa8c4, #BAA8C4);
  fill-rule: evenodd;
  d: path("M35.685 6.082a7.003 7.003 0 0 1-8.78 4.599a8.5 8.5 0 0 1 8.78-4.599");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.tqd0thb1b {
  stop-color: var(--svg-color--fffcff, #FFFCFF);
}

.tv1ac5b3z {
  stop-color: var(--svg-color--bc96e3, #BC96E3);
}

.u-l9_7bkh {
  stop-color: var(--svg-color--ebe9ed, #EBE9ED);
}

.u8k7ndb0e {
  stop-color: var(--svg-color--d4cddb, #D4CDDB);
}

.v1avyhbkf {
  cx: 29px;
  cy: 27px;
  r: 7px;
}

.v6qe5cb6n {
  fill: var(--svg-color--baa6ba, #BAA6BA);
  fill-rule: evenodd;
  d: path("M26.114 20.62A7 7 0 0 1 29 20a7 7 0 0 1 6.135 3.627a5.502 5.502 0 0 1-9.021-3.007");
}

.v8vr1yqak {
  cx: 3px;
  cy: 6px;
  r: 3px;
  fill: var(--svg-color--fff, #fff);
}

.var8tmbqw {
  cx: 32.5px;
  cy: 19.5px;
  r: 5.25px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vqw_5qb-n {
  cx: -2px;
  cy: 10px;
  r: 7px;
}

.w2ofxobzx {
  stop-color: var(--svg-color--dddbe0, #DDDBE0);
}

.w6gnd3b1h {
  cx: 6.5px;
  cy: 2.5px;
  r: 7.5px;
}

.x470zsbyg {
  stop-color: var(--svg-color--d3c5e0, #D3C5E0);
}

.x8o28pbmn {
  stop-color: var(--svg-color--b897cd, #B897CD);
}

.xhfle5sqo {
  stop-color: var(--svg-color--c1afd1, #C1AFD1);
}

.xmcpyxr8e {
  fill: var(--svg-color--ac8cc6, #AC8CC6);
  fill-rule: evenodd;
  d: path("M10.84 29.218a4.5 4.5 0 1 1 8.467-3.026a8.5 8.5 0 1 1-8.467 3.026");
}

.z1spwobwt {
  cx: 19.5px;
  cy: -0.5px;
  r: 6.5px;
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zu1-lrb6f {
  stop-color: var(--svg-color--e9e1f0, #E9E1F0);
}

</style>
