<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><circle fill="url(#ixkd9Gd)" class="motv4wboz"/><circle fill="url(#ip0a4Zc)" class="ihfq4mlyi"/><path class="uhfgxvb8v"/><path fill="url(#irplZdd)" class="g-dotzwlt"/><path fill="url(#irplZdd)" class="vn9csdbxy"/><path fill="url(#i2u57dd)" class="zrp_wcc4v"/><path fill="url(#iAuD0Sd)" class="qkc9gnbyc"/><g filter="url(#iCilKlb)" class="mc2zb0bvp"><path class="ft_ntu_rb"/></g><path fill="url(#iZ8EXsc)" class="orxee1j6a"/><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="ixkd9Gd" cx="0" cy="0" r="1" gradientTransform="rotate(135 4.3 7.513)scale(9.10579 4.71285)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="ip0a4Zc" cx="0" cy="0" r="1" gradientTransform="rotate(135 9.069 9.99)scale(7.66968 4.32966)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="i2u57dd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.55556 17.1111 0 15.999 27.556)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="iAuD0Sd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -9.5 16.51504 -.86922 16.5 30)" gradientUnits="userSpaceOnUse"><stop class="yui1fntgg"/><stop offset=".766" class="i3nb-2ysz"/><stop offset=".864" class="p_bns_tff"/><stop offset=".886" class="twpub9y2u"/></radialGradient><linearGradient id="irplZdd" x1="16.5" x2="15.5" y1="8" y2="15" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><linearGradient id="iZ8EXsc" x1="15.999" x2="15.999" y1="19" y2="20.43" gradientUnits="userSpaceOnUse"><stop class="nvahlubfz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><filter id="iCilKlb" width="4.724" height="5.447" x="16.776" y="22.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_20" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:face-with-tongue" /></template>
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

.ehgdi7b0u {
  stop-color: var(--svg-color--553b3e, #553B3E);
}

.fqac_w1ss {
  stop-color: var(--svg-color--c87928, #C87928);
  stop-opacity: 0;
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft_ntu_rb {
  stroke: var(--svg-color--fff, #fff);
  d: path("M18 26.5c1-.5 2-1.5 2-3");
}

.ft5dv1b6b {
  fill: none;
}

.g-dotzwlt {
  d: path("M11 15a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.i3nb-2ysz {
  stop-color: var(--svg-color--ff2b8f, #FF2B8F);
}

.ihfq4mlyi {
  cx: 19.244px;
  cy: 13.943px;
  r: 4.244px;
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

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.motv4wboz {
  cx: 9.017px;
  cy: 13.421px;
  r: 4.673px;
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.nvahlubfz {
  stop-color: var(--svg-color--eccdff, #ECCDFF);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.orxee1j6a {
  d: path("M22.859 20.43c.09-.46.14-.94.14-1.43h-14c0 .49.05.96.14 1.43z");
}

.p_bns_tff {
  stop-color: var(--svg-color--bb0773, #BB0773);
}

.qkc9gnbyc {
  d: path("M16.016 29c4.2 0 4.87-4.2 5-5.25c.1-.85-.35-1.28-.84-1.57s-1.96-.56-4.16-.56s-3.66.27-4.16.56s-.95.72-.84 1.57c.13 1.05.8 5.25 5 5.25");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.twpub9y2u {
  stop-color: var(--svg-color--9f0762, #9F0762);
}

.uhfgxvb8v {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.42 16.224a4.206 4.206 0 1 0 0-8.411a4.206 4.206 0 0 0 0 8.411m11.148.077a4.244 4.244 0 1 0 0-8.489a4.244 4.244 0 0 0 0 8.49");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vn9csdbxy {
  d: path("M21 15a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.yui1fntgg {
  stop-color: var(--svg-color--ff1c4a, #FF1C4A);
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

.zrp_wcc4v {
  d: path("M15.999 26c-7 0-7-7-7-7h14s0 7-7 7");
}

</style>
