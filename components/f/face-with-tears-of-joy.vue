<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><g filter="url(#iWGKwqd)" class="mc2zb0bvp"><path class="bo-hfpbkv"/></g><g filter="url(#ilWJWPc)" class="mc2zb0bvp"><path class="a79h18b3f"/></g><path class="kj167yb9b"/><g filter="url(#iXU3iJe)" class="qfgt6tb2e"><path class="ca3x0hbrn"/></g><path class="ij5txvb3z"/><g filter="url(#iqwNQNc)" class="qfgt6tb2e"><path class="ti57i9b9x"/></g><path fill="url(#iUQOPic)" class="wbzw-bbbe"/><path fill="url(#iGCY4Xv)" class="u85nt16hr"/><path fill="url(#igB76ib)" clip-rule="evenodd" class="v988obcng"/><path fill="url(#iYw7JZb)" clip-rule="evenodd" class="s5xf0gwfe"/><path fill="url(#iPglxwc)" class="ijvvcjb5t"/><path fill="url(#iK2sIZc)" class="axxuql04j"/><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iUQOPic" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11 22 0 16 27)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="igB76ib" cx="0" cy="0" r="1" gradientTransform="matrix(4 -2.5 1.62283 2.59652 4 19.5)" gradientUnits="userSpaceOnUse"><stop class="p4vnlcfhl"/><stop offset="1" class="cr309tbhd"/></radialGradient><radialGradient id="iYw7JZb" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 3 -1.94739 2.92108 25.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="p4vnlcfhl"/><stop offset="1" class="cr309tbhd"/></radialGradient><radialGradient id="iPglxwc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.50001 3.49998 -1.59351 -2.50411 8 15)" gradientUnits="userSpaceOnUse"><stop class="ex5w2u-ri"/><stop offset="1" class="uospscb_d"/></radialGradient><radialGradient id="iK2sIZc" cx="0" cy="0" r="1" gradientTransform="matrix(3 3.5 -1.59352 1.36587 27.5 15.5)" gradientUnits="userSpaceOnUse"><stop class="i97_rac7h"/><stop offset="1" class="yco627brm"/></radialGradient><filter id="iWGKwqd" width="10" height="7" x="5" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_377" stdDeviation=".75"/></filter><filter id="ilWJWPc" width="10.001" height="7" x="16" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_377" stdDeviation=".75"/></filter><filter id="iXU3iJe" width="8.75" height="5.75" x="6.375" y="6.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_377" stdDeviation=".75"/></filter><filter id="iqwNQNc" width="8.75" height="5.75" x="17.375" y="6.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_377" stdDeviation=".75"/></filter><linearGradient id="iGCY4Xv" x1="16" x2="16" y1="16" y2="17.5" gradientUnits="userSpaceOnUse"><stop class="nvahlubfz"/><stop offset="1" class="vc--wpv5i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:face-with-tears-of-joy" /></template>
<style>
.a79h18b3f {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 11.5s.5-2 2.5-2s2.5 2 2.5 2");
}

.axxuql04j {
  d: path("m24.25 17l3.37 3.37a2.121 2.121 0 1 0 3-3L27.25 14a2.121 2.121 0 0 0-3 3");
}

.bo-hfpbkv {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 11.5s.25-2 2.5-2s2.5 2 2.5 2");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.ca3x0hbrn {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M8.25 10.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.cr309tbhd {
  stop-color: var(--svg-color--ff822d, #FF822D);
  stop-opacity: 0;
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.ex5w2u-ri {
  stop-color: var(--svg-color--508fff, #508FFF);
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

.i97_rac7h {
  stop-color: var(--svg-color--5092ff, #5092FF);
}

.ij5txvb3z {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 11s.5-2 2.5-2s2.5 2 2.5 2");
}

.ijvvcjb5t {
  d: path("m8 17l-3.37 3.37a2.121 2.121 0 1 1-3-3L5 14a2.121 2.121 0 0 1 3 3");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kj167yb9b {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 11s.25-2 2.5-2s2.5 2 2.5 2");
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

.nvahlubfz {
  stop-color: var(--svg-color--eccdff, #ECCDFF);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.p4vnlcfhl {
  stop-color: var(--svg-color--6d4534, #6D4534);
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

.s5xf0gwfe {
  fill-rule: evenodd;
  d: path("M29.875 18.125L26.75 15a2.121 2.121 0 0 0-3 3l3.37 3.37a2.12 2.12 0 0 0 1.81.598c.471-1.197.786-2.488.945-3.843");
}

.ti57i9b9x {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M19.25 10.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.u85nt16hr {
  d: path("M8 16.5V16h16v.5a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1");
}

.uospscb_d {
  stop-color: var(--svg-color--3d5bf1, #3D5BF1);
}

.v988obcng {
  fill-rule: evenodd;
  d: path("M2.938 21.625a2.12 2.12 0 0 0 2.692-.255L9 18a2.121 2.121 0 1 0-3-3l-3.37 3.37c-.164.164-.296.35-.396.547c.157.941.391 1.847.704 2.708");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wbzw-bbbe {
  d: path("M16 25c-9 0-9-9-9-9h18s0 9-9 9");
}

.yco627brm {
  stop-color: var(--svg-color--3f5fff, #3F5FFF);
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
