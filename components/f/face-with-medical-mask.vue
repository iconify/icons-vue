<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path fill="url(#iDyuLFv)" class="eqw3aac0j"/><path fill="url(#iATCDzc)" class="drn5dq16j"/><g filter="url(#ikcLC5d)" class="mc2zb0bvp"><path class="mbmzl-bfe"/></g><g filter="url(#iet7CxS)" class="mc2zb0bvp"><path class="sko63_bie"/></g><path class="pv1wk-bbk"/><g filter="url(#iPdNfVd)" class="qfgt6tb2e"><path class="y3alaib6w"/></g><path class="f4scbebmy"/><g filter="url(#iQwdMMd)" class="qfgt6tb2e"><path class="g3q6qab9r"/></g><path stroke="url(#ibP05he)" class="ovdk3xbkl"/><path stroke="url(#iNxwQEc)" class="svy0j65lh"/><path fill="url(#ij88Vod)" class="q235bpb7j"/><path fill="url(#itRr58d)" clip-rule="evenodd" class="w1m4hqbfe"/><path fill="url(#i63UiMd)" clip-rule="evenodd" class="jxu6q6bax"/><path fill="url(#ingVOzb)" clip-rule="evenodd" class="nw-jiybcw"/><path fill="url(#iqa4k5b)" clip-rule="evenodd" class="tqll_aboy"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iDyuLFv" cx="0" cy="0" r="1" gradientTransform="translate(7.505 16.501)scale(6.49487)" gradientUnits="userSpaceOnUse"><stop class="bxihbocks"/><stop offset="1" class="otvlrubyy"/></radialGradient><radialGradient id="iATCDzc" cx="0" cy="0" r="1" gradientTransform="translate(24.505 16.501)scale(6.49487)" gradientUnits="userSpaceOnUse"><stop class="bxihbocks"/><stop offset="1" class="otvlrubyy"/></radialGradient><linearGradient id="ibP05he" x1="6.833" x2="6.833" y1="10.4" y2="8.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><linearGradient id="iNxwQEc" x1="25.167" x2="25.167" y1="10.4" y2="8.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><linearGradient id="ij88Vod" x1="8.5" x2="24" y1="23.5" y2="17" gradientUnits="userSpaceOnUse"><stop class="tsvdi327d"/><stop offset="1" class="dbgwfjgev"/></linearGradient><linearGradient id="itRr58d" x1="3" x2="8" y1="22.5" y2="22.5" gradientUnits="userSpaceOnUse"><stop class="ishu1mb_u"/><stop offset="1" class="q7b4zsbcf"/></linearGradient><linearGradient id="i63UiMd" x1="1.5" x2="8.5" y1="12.5" y2="17" gradientUnits="userSpaceOnUse"><stop class="ezsgkabgs"/><stop offset="1" class="aarfi3b6k"/></linearGradient><linearGradient id="ingVOzb" x1="24" x2="30.5" y1="16.5" y2="12.5" gradientUnits="userSpaceOnUse"><stop class="r-tkzpbkg"/><stop offset="1" class="bqrlexbod"/></linearGradient><linearGradient id="iqa4k5b" x1="30" x2="25" y1="22.5" y2="22.5" gradientUnits="userSpaceOnUse"><stop class="eeio61q0d"/><stop offset="1" class="najq7ubfc"/></linearGradient><filter id="ikcLC5d" width="10" height="7" x="5" y="8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_96" stdDeviation=".75"/></filter><filter id="iet7CxS" width="10.001" height="7" x="16" y="8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_96" stdDeviation=".75"/></filter><filter id="iPdNfVd" width="8.75" height="5.75" x="6.375" y="7.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_96" stdDeviation=".75"/></filter><filter id="iQwdMMd" width="8.75" height="5.75" x="17.375" y="7.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_96" stdDeviation=".75"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:face-with-medical-mask" /></template>
<style>
.aarfi3b6k {
  stop-color: var(--svg-color--e3c1ff, #E3C1FF);
}

.bqrlexbod {
  stop-color: var(--svg-color--d7d7d7, #D7D7D7);
}

.bxihbocks {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
  stop-opacity: 0.59;
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.dbgwfjgev {
  stop-color: var(--svg-color--f3eff9, #F3EFF9);
}

.drn5dq16j {
  d: path("M24.5 23a6.5 6.5 0 1 0 0-13a6.5 6.5 0 0 0 0 13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.eeio61q0d {
  stop-color: var(--svg-color--e1ccf6, #E1CCF6);
}

.eqw3aac0j {
  d: path("M7.5 23a6.5 6.5 0 1 0 0-13a6.5 6.5 0 0 0 0 13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ezsgkabgs {
  stop-color: var(--svg-color--d5a4a9, #D5A4A9);
}

.f4scbebmy {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 12s.5-2 2.5-2s2.5 2 2.5 2");
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g3q6qab9r {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M19.25 11.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.ii_r00eab {
  stop-color: var(--svg-color--524049, #524049);
}

.ishu1mb_u {
  stop-color: var(--svg-color--bb8fc3, #BB8FC3);
}

.jxu6q6bax {
  fill-rule: evenodd;
  d: path("m2.167 13.523l6.063 3.898l.54-.842l-6.419-4.126a16 16 0 0 0-.184 1.07");
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

.mbmzl-bfe {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 12.5s.25-2 2.5-2s2.5 2 2.5 2");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.najq7ubfc {
  stop-color: var(--svg-color--f1e7fa, #F1E7FA);
}

.nw-jiybcw {
  fill-rule: evenodd;
  d: path("M29.647 12.454L23.23 16.58l.54.842l6.06-3.896q-.074-.544-.183-1.07");
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.otvlrubyy {
  stop-color: var(--svg-color--ff6dc6, #FF6DC6);
  stop-opacity: 0;
}

.ovdk3xbkl {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.5 9.5c.333-1 1.6-3 4-3");
}

.pv1wk-bbk {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 12s.25-2 2.5-2s2.5 2 2.5 2");
}

.q235bpb7j {
  d: path("M8 17.562a2 2 0 0 1 1.515-1.94l4.545-1.137a8 8 0 0 1 3.88 0l4.545 1.136A2 2 0 0 1 24 17.561v6.053a2 2 0 0 1-1.298 1.873l-1.084.406a16 16 0 0 1-11.236 0l-1.084-.406A2 2 0 0 1 8 23.614z");
}

.q7b4zsbcf {
  stop-color: var(--svg-color--e1bbff, #E1BBFF);
}

.qfgt6tb2e {
  opacity: var(--svg-opacity--0-26, 0.26);
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.r-tkzpbkg {
  stop-color: var(--svg-color--f3edfa, #F3EDFA);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.sko63_bie {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 12.5s.5-2 2.5-2s2.5 2 2.5 2");
}

.svy0j65lh {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.5 9.5c-.333-1-1.6-3-4-3");
}

.tqll_aboy {
  fill-rule: evenodd;
  d: path("M28.918 22H24v1h4.475q.24-.488.443-1");
}

.tsvdi327d {
  stop-color: var(--svg-color--dfb6ff, #DFB6FF);
}

.w1m4hqbfe {
  fill-rule: evenodd;
  d: path("M3.523 23H9v-1H3.08q.203.512.443 1");
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.y3alaib6w {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M8.25 11.75s.25-2 2.5-2s2.5 2 2.5 2");
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
