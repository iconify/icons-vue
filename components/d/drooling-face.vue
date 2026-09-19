<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><g filter="url(#iNa0hed)" class="mc2zb0bvp"><path class="qojucht1d"/></g><g filter="url(#iwobEgc)" class="mc2zb0bvp"><path class="u-yj7_82v"/></g><path class="xtack1onm"/><g filter="url(#i4pTbAc)" class="qfgt6tb2e"><path class="okd8dx-zc"/></g><path class="akel7_bww"/><g filter="url(#iy582de)" class="qfgt6tb2e"><path class="sfs7bzvxh"/></g><path stroke="url(#ikDt9cz)" class="zacs9cbft"/><path stroke="url(#iMLnlLd)" class="z1r5nfb4z"/><path fill="url(#iof2llb)" class="ealabbc1n"/><path fill="url(#id2tsJe)" class="x-0uppb2r"/><path fill="url(#iHhXl0b)" clip-rule="evenodd" class="yw7byhzbx"/><path fill="url(#imjanId)" clip-rule="evenodd" class="yw7byhzbx"/><path fill="url(#iRMecoc)" clip-rule="evenodd" class="y8cn5dpkv"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iof2llb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.72 6 -4.0534 -3.18867 19.72 21.5)" gradientUnits="userSpaceOnUse"><stop class="q-ke03b6w"/><stop offset="1" class="j7t0n7b5u"/></radialGradient><radialGradient id="id2tsJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.5 15 0 16 25.5)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="imjanId" cx="0" cy="0" r="1" gradientTransform="matrix(0 3 -1.74841 0 16 23.5)" gradientUnits="userSpaceOnUse"><stop class="qp4iu1brs"/><stop offset="1" class="x8bkgd0rp"/></radialGradient><radialGradient id="iRMecoc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.5 -1.00005 1.03315 -7.74822 23.5 26)" gradientUnits="userSpaceOnUse"><stop offset=".408" class="y8xu91b7l"/><stop offset=".574" class="h9chzcc_v"/><stop offset=".74" class="fbjcupbzm"/><stop offset=".9" class="kgt5nyy5c"/><stop offset="1" class="o1lyi1bhj"/></radialGradient><filter id="iNa0hed" width="10" height="7" x="5" y="9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_84" stdDeviation=".75"/></filter><filter id="iwobEgc" width="10.001" height="7" x="16" y="9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_84" stdDeviation=".75"/></filter><filter id="i4pTbAc" width="8.75" height="5.75" x="6.375" y="8.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_84" stdDeviation=".75"/></filter><filter id="iy582de" width="8.75" height="5.75" x="17.375" y="8.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_84" stdDeviation=".75"/></filter><linearGradient id="ikDt9cz" x1="6.833" x2="6.833" y1="11.4" y2="9.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><linearGradient id="iMLnlLd" x1="25.167" x2="25.167" y1="11.4" y2="9.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><linearGradient id="iHhXl0b" x1="16" x2="16" y1="22" y2="25" gradientUnits="userSpaceOnUse"><stop class="v3ns1qbxq"/><stop offset=".16" class="p3d6msqiq"/><stop offset=".254" class="swpvvqb4b"/><stop offset=".535" class="x7n6jgbds"/><stop offset="1" class="hqyd5pf2o"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:drooling-face" /></template>
<style>
.akel7_bww {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 13s.5-2 2.5-2s2.5 2 2.5 2");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.ealabbc1n {
  d: path("M11.62 21.5h6.48l1.62 2.903v6.704L11.62 29z");
}

.fbjcupbzm {
  stop-color: var(--svg-color--3c6bf7, #3C6BF7);
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.h9chzcc_v {
  stop-color: var(--svg-color--4889ff, #4889FF);
}

.hqyd5pf2o {
  stop-color: var(--svg-color--3e69ff, #3E69FF);
}

.ii_r00eab {
  stop-color: var(--svg-color--524049, #524049);
}

.j7t0n7b5u {
  stop-color: var(--svg-color--c20a78, #C20A78);
  stop-opacity: 0;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kgt5nyy5c {
  stop-color: var(--svg-color--3f72ff, #3F72FF);
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

.o1lyi1bhj {
  stop-color: var(--svg-color--3156fe, #3156FE);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.okd8dx-zc {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M8.25 12.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.p3d6msqiq {
  stop-color: var(--svg-color--3e7aff, #3E7AFF);
}

.q-ke03b6w {
  stop-color: var(--svg-color--c20aa5, #C20AA5);
}

.qfgt6tb2e {
  opacity: var(--svg-opacity--0-26, 0.26);
}

.qojucht1d {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 13.5s.25-2 2.5-2s2.5 2 2.5 2");
}

.qp4iu1brs {
  stop-color: var(--svg-color--323fff, #323FFF);
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.sfs7bzvxh {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M19.25 12.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.swpvvqb4b {
  stop-color: var(--svg-color--4588ff, #4588FF);
}

.u-yj7_82v {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 13.5s.5-2 2.5-2s2.5 2 2.5 2");
}

.v3ns1qbxq {
  stop-color: var(--svg-color--2962f3, #2962F3);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.x-0uppb2r {
  d: path("M16 25c-7 0-7-7-7-7h14s0 7-7 7");
}

.x7n6jgbds {
  stop-color: var(--svg-color--4170ff, #4170FF);
}

.x8bkgd0rp {
  stop-color: var(--svg-color--323fff, #323FFF);
  stop-opacity: 0;
}

.xtack1onm {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 13s.25-2 2.5-2s2.5 2 2.5 2");
}

.y8cn5dpkv {
  fill-rule: evenodd;
  d: path("M16 23.5v1.75c0 .414.336.75.75.75h.083c.369 0 .667.299.667.667v.083a1.25 1.25 0 1 0 2.5 0v-2.813A6 6 0 0 0 21.85 22H17.5a1.5 1.5 0 0 0-1.5 1.5");
}

.y8xu91b7l {
  stop-color: var(--svg-color--325cff, #325CFF);
}

.yw7byhzbx {
  fill-rule: evenodd;
  d: path("M10.15 22c.95 1.568 2.684 3 5.85 3s4.9-1.432 5.85-3z");
}

.z1r5nfb4z {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.5 10.5c-.333-1-1.6-3-4-3");
}

.zacs9cbft {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.5 10.5c.333-1 1.6-3 4-3");
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zg8znn0_h {
  stop-color: var(--svg-color--4a2c42, #4A2C42);
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
