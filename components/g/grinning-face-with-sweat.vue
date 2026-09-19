<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><g filter="url(#iSpMftc)" class="mc2zb0bvp"><path class="nouvix7gl"/></g><g filter="url(#iTARLHc)" class="mc2zb0bvp"><path class="i33tbmmkg"/></g><path class="w7v3e39wv"/><g filter="url(#iadzi1b)" class="qfgt6tb2e"><path class="jzya5_wbc"/></g><path class="t8ql4fbwv"/><g filter="url(#ilqrzie)" class="qfgt6tb2e"><path class="xotl4qbgf"/></g><path fill="url(#iUQOPic)" class="wbzw-bbbe"/><path fill="url(#iGCY4Xv)" class="u85nt16hr"/><path fill="url(#iQrI5Ce)" clip-rule="evenodd" class="u6mt0lx9a"/><rect fill="url(#i2UqeEc)" class="fusdjwb5z"/></g><defs><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iUQOPic" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11 22 0 16 27)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="iQrI5Ce" cx="0" cy="0" r="1" gradientTransform="matrix(-3.49999 10 -4.62034 -1.61711 26.5 4.5)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="i2UqeEc" cx="0" cy="0" r="1" gradientTransform="rotate(103.449 13.115 12.34)scale(10.7493 3.72027)" gradientUnits="userSpaceOnUse"><stop class="flip35zyj"/><stop offset=".806" class="uospscb_d"/><stop offset=".962" class="mqyq9nueh"/></radialGradient><filter id="iSpMftc" width="10" height="7" x="6" y="9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_367" stdDeviation=".75"/></filter><filter id="iTARLHc" width="10.001" height="7" x="15" y="9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_367" stdDeviation=".75"/></filter><filter id="iadzi1b" width="8.75" height="5.75" x="7.375" y="8.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_367" stdDeviation=".75"/></filter><filter id="ilqrzie" width="8.75" height="5.75" x="16.375" y="8.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_367" stdDeviation=".75"/></filter><linearGradient id="iGCY4Xv" x1="16" x2="16" y1="16" y2="17.5" gradientUnits="userSpaceOnUse"><stop class="nvahlubfz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:grinning-face-with-sweat" /></template>
<style>
.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.d3wf5jb8r {
  stop-color: var(--svg-color--392108, #392108);
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.flip35zyj {
  stop-color: var(--svg-color--5c98ff, #5C98FF);
}

.fqac_w1ss {
  stop-color: var(--svg-color--c87928, #C87928);
  stop-opacity: 0;
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.fusdjwb5z {
  width: 5px;
  height: 10px;
  x: 24px;
  y: 2px;
  rx: 2.5px;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.i33tbmmkg {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 13.5s.5-2 2.5-2s2.5 2 2.5 2");
}

.jzya5_wbc {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M9.25 12.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.mqyq9nueh {
  stop-color: var(--svg-color--6065ca, #6065CA);
}

.nouvix7gl {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 13.5s.25-2 2.5-2s2.5 2 2.5 2");
}

.nvahlubfz {
  stop-color: var(--svg-color--eccdff, #ECCDFF);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.qfgt6tb2e {
  opacity: var(--svg-opacity--0-26, 0.26);
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.t8ql4fbwv {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 13s.5-2 2.5-2s2.5 2 2.5 2");
}

.u6mt0lx9a {
  fill-rule: evenodd;
  d: path("M22 3.05c-.619.632-1 1.496-1 2.45v7a3.5 3.5 0 1 0 7 0V8.122c-1.333-2.246-3.333-4.023-6-5.071");
}

.u85nt16hr {
  d: path("M8 16.5V16h16v.5a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1");
}

.uospscb_d {
  stop-color: var(--svg-color--3d5bf1, #3D5BF1);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.w7v3e39wv {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 13s.25-2 2.5-2s2.5 2 2.5 2");
}

.wbzw-bbbe {
  d: path("M16 25c-9 0-9-9-9-9h18s0 9-9 9");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xotl4qbgf {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M18.25 12.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
