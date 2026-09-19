<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><circle fill="url(#i3Aigyo)" class="qiljljbln"/><circle fill="url(#ijO1FUd)" class="eal5ll7-q"/><path class="h9iiy9t5d"/><path fill="url(#iAQEgcs)" class="fr_40pbdn"/><path fill="url(#iAQEgcs)" class="j4u4wbcfb"/><path stroke="url(#ikDt9cz)" class="zacs9cbft"/><path stroke="url(#iMLnlLd)" class="z1r5nfb4z"/><path stroke="url(#i00GOde)" class="l86hvnbre"/><rect fill="url(#ipKsS0b)" class="l4fzof7tn"/><rect fill="url(#iCoVQKe)" class="glctrobti"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="i3Aigyo" cx="0" cy="0" r="1" gradientTransform="rotate(135 3.678 9.013)scale(9.10579 4.71285)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="ijO1FUd" cx="0" cy="0" r="1" gradientTransform="rotate(135 8.447 11.49)scale(7.66968 4.32966)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="ipKsS0b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49999 5.5 -2.42653 -.66177 7.75 21.25)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="iCoVQKe" cx="0" cy="0" r="1" gradientTransform="rotate(105.285 -2.707 13.222)scale(7.58655 2.95188)" gradientUnits="userSpaceOnUse"><stop class="flip35zyj"/><stop offset=".806" class="uospscb_d"/><stop offset=".962" class="mqyq9nueh"/></radialGradient><linearGradient id="iAQEgcs" x1="16.5" x2="15.5" y1="11" y2="18" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><linearGradient id="ikDt9cz" x1="6.833" x2="6.833" y1="11.4" y2="9.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><linearGradient id="iMLnlLd" x1="25.167" x2="25.167" y1="11.4" y2="9.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><linearGradient id="i00GOde" x1="16" x2="16" y1="20" y2="22" gradientUnits="userSpaceOnUse"><stop class="da3dd5b9t"/><stop offset="1" class="nflylhbjg"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crying-face" /></template>
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

.da3dd5b9t {
  stop-color: var(--svg-color--4f3c43, #4F3C43);
}

.eal5ll7-q {
  cx: 19.244px;
  cy: 16.943px;
  r: 4.244px;
}

.ehgdi7b0u {
  stop-color: var(--svg-color--553b3e, #553B3E);
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

.fr_40pbdn {
  d: path("M11 18a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.ft5dv1b6b {
  fill: none;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.glctrobti {
  width: 4px;
  height: 7px;
  x: 6px;
  y: 19px;
  rx: 2px;
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.h9iiy9t5d {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.42 19.224a4.206 4.206 0 1 0 0-8.411a4.206 4.206 0 0 0 0 8.411m11.148.077a4.244 4.244 0 1 0 0-8.489a4.244 4.244 0 0 0 0 8.49");
}

.ii_r00eab {
  stop-color: var(--svg-color--524049, #524049);
}

.j4u4wbcfb {
  d: path("M21 18a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kiu9e17zs {
  stop-color: var(--svg-color--3d2432, #3D2432);
}

.l4fzof7tn {
  width: 4px;
  height: 7px;
  x: 5px;
  y: 20px;
  rx: 2px;
}

.l86hvnbre {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 23s1-1 3-1s3 1 3 1");
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.mqyq9nueh {
  stop-color: var(--svg-color--6065ca, #6065CA);
}

.nflylhbjg {
  stop-color: var(--svg-color--512756, #512756);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.qiljljbln {
  cx: 9.017px;
  cy: 16.42px;
  r: 4.673px;
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.uospscb_d {
  stop-color: var(--svg-color--3d5bf1, #3D5BF1);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
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
