<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><circle fill="url(#iGpZLse)" class="mv_citbmv"/><circle fill="url(#io7cAZd)" class="nmnni6m-k"/><path class="j-c6jjbfw"/><path fill="url(#iunXZ9c)" class="wcixllbrc"/><path fill="url(#iunXZ9c)" class="hgg_kpg5o"/><rect fill="url(#iUVROnR)" class="d_s7fubez"/><rect fill="url(#idriR0M)" class="fyv4p7b4a"/><path fill="url(#ixGNekJ)" clip-rule="evenodd" class="k01e28bqd"/><path stroke="url(#io8rr9d)" class="nwtjpx0gd"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iGpZLse" cx="0" cy="0" r="1" gradientTransform="rotate(135 4.557 7.225)scale(9.74236 5.04232)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="io7cAZd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.75 5.75 -3.24597 -3.24597 23 10)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="iUVROnR" cx="0" cy="0" r="1" gradientTransform="matrix(8.5 0 0 4.87224 17.5 19)" gradientUnits="userSpaceOnUse"><stop class="afbh4nbhl"/><stop offset="1" class="fru8ojb7r"/></radialGradient><radialGradient id="ixGNekJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.50001 1.7 -2.125 -.62502 30.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="js8f2rbxq"/><stop offset="1" class="oiiegxn4l"/></radialGradient><linearGradient id="iunXZ9c" x1="20.615" x2="19.927" y1="11" y2="15.03" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><linearGradient id="idriR0M" x1="22.497" x2="22.497" y1="15.324" y2="19.986" gradientUnits="userSpaceOnUse"><stop class="akyog32et"/><stop offset=".419" class="uu107ybwe"/><stop offset=".801" class="r_ww_9uol"/><stop offset="1" class="c1vn2dbed"/></linearGradient><linearGradient id="io8rr9d" x1="16" x2="16" y1="21" y2="23" gradientUnits="userSpaceOnUse"><stop class="da3dd5b9t"/><stop offset="1" class="nflylhbjg"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:lying-face" /></template>
<style>
.afbh4nbhl {
  stop-color: var(--svg-color--ea7545, #EA7545);
}

.akyog32et {
  stop-color: var(--svg-color--f2bd4b, #F2BD4B);
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.c1vn2dbed {
  stop-color: var(--svg-color--f57c6c, #F57C6C);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.d_s7fubez {
  width: 20px;
  height: 20px;
  x: 8px;
  y: 8px;
  rx: 10px;
}

.d3wf5jb8r {
  stop-color: var(--svg-color--392108, #392108);
}

.da3dd5b9t {
  stop-color: var(--svg-color--4f3c43, #4F3C43);
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

.fru8ojb7r {
  stop-color: var(--svg-color--e86f48, #E86F48);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyv4p7b4a {
  width: 19px;
  height: 5px;
  x: 13px;
  y: 15px;
  rx: 2.5px;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hgg_kpg5o {
  d: path("M20 15a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.j-c6jjbfw {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.5 16a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m11 0a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9");
}

.js8f2rbxq {
  stop-color: var(--svg-color--ffda66, #FFDA66);
}

.k01e28bqd {
  fill-rule: evenodd;
  d: path("M29.739 19.989A3 3 0 0 1 27.764 15H29.5a2.5 2.5 0 0 1 .239 4.989");
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

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.mv_citbmv {
  cx: 9px;
  cy: 13px;
  r: 5px;
}

.nflylhbjg {
  stop-color: var(--svg-color--512756, #512756);
}

.nmnni6m-k {
  cx: 19.5px;
  cy: 13.5px;
  r: 4.5px;
}

.nwtjpx0gd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 24c.333-.667 1.6-2 4-2s3.667 1.333 4 2");
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.oiiegxn4l {
  stop-color: var(--svg-color--ffda62, #FFDA62);
  stop-opacity: 0;
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.r_ww_9uol {
  stop-color: var(--svg-color--ff9b60, #FF9B60);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.uu107ybwe {
  stop-color: var(--svg-color--ffae4b, #FFAE4B);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wcixllbrc {
  d: path("M12 15a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
