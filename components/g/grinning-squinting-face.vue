<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path fill="url(#iT7tYxb)" class="isvj7ibov"/><path fill="url(#iGCY4Xv)" class="unsya9bva"/><g filter="url(#iRvL60c)" class="ljb4srbfs"><path fill="url(#ijpXHec)" class="t22krebtu"/><path fill="url(#ijpXHec)" class="oqzd2gbnc"/></g><path fill="url(#icvPxoc)" class="xv_ozxxod"/><path fill="url(#isHkUwb)" class="lx25atb0r"/><g filter="url(#itDc2Sc)"><path fill="url(#iyQ2Z9b)" class="mtcm8s2ci"/><path fill="url(#iyQ2Z9b)" class="abbnjibdo"/></g><path fill="url(#iw4B9Zc)" class="u_7j5_n6g"/><path fill="url(#iO0dltc)" class="th5t3jbwq"/><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iT7tYxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.2222 24.4444 0 16 28.222)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="ijpXHec" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62502 7.125 -9.31237 -3.4309 9.781 8.438)" gradientUnits="userSpaceOnUse"><stop class="vn4n3no1s"/><stop offset=".889" class="ixmaddcbc"/></radialGradient><radialGradient id="iyQ2Z9b" cx="0" cy="0" r="1" gradientTransform="rotate(-135.995 16.533 2.298)scale(13.3597 17.4611)" gradientUnits="userSpaceOnUse"><stop class="kb93-db6z"/><stop offset=".802" class="z-xmlwmhd"/></radialGradient><linearGradient id="iGCY4Xv" x1="16" x2="16" y1="16" y2="17.5" gradientUnits="userSpaceOnUse"><stop class="nvahlubfz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="icvPxoc" x1="10.578" x2="8" y1="14.732" y2="9.388" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="isHkUwb" x1="8.86" x2="11.25" y1="11.139" y2="6.451" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iw4B9Zc" x1="21.406" x2="23.985" y1="14.732" y2="9.388" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iO0dltc" x1="23.125" x2="20.734" y1="11.139" y2="6.451" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><filter id="iRvL60c" width="7" height="6.996" x="7.5" y="7.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_362" stdDeviation=".25"/></filter><filter id="itDc2Sc" width="7" height="6.996" x="16.906" y="7.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_362" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:grinning-squinting-face" /></template>
<style>
.abbnjibdo {
  d: path("M21.959 8.543a1 1 0 0 1 .895 1.79l-2.207 1.102h-3.24a1 1 0 0 1 .552-.892z");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
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

.gvfj_gdms {
  stop-color: var(--svg-color--503a4a, #503A4A);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.isvj7ibov {
  d: path("M16 26C6 26 6 16 6 16h20s0 10-10 10");
}

.ixmaddcbc {
  stop-color: var(--svg-color--9f5e0f, #9F5E0F);
  stop-opacity: 0;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kb93-db6z {
  stop-color: var(--svg-color--e9830a, #E9830A);
}

.ljb4srbfs {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
}

.lx25atb0r {
  d: path("M9.447 8.106a1 1 0 0 0-.894 1.789l2.206 1.103H14a1 1 0 0 0-.553-.892z");
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.mtcm8s2ci {
  d: path("M21.959 14.328a1 1 0 0 0 .895-1.79l-2.207-1.103h-3.24a1 1 0 0 0 .552.893z");
}

.nvahlubfz {
  stop-color: var(--svg-color--eccdff, #ECCDFF);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.oqzd2gbnc {
  d: path("M9.447 8.543a1 1 0 0 0-.894 1.79l2.206 1.102H14a1 1 0 0 0-.553-.892z");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.t22krebtu {
  d: path("M9.447 14.328a1 1 0 1 1-.894-1.79l2.206-1.103H14a1 1 0 0 1-.553.893z");
}

.th5t3jbwq {
  d: path("M22.537 8.106a1 1 0 0 1 .895 1.789l-2.207 1.103h-3.24a1 1 0 0 1 .552-.892z");
}

.u_7j5_n6g {
  d: path("M22.537 13.89a1 1 0 1 0 .895-1.789l-2.207-1.103h-3.24a1 1 0 0 0 .552.892z");
}

.unsya9bva {
  d: path("M23.5 17.5h-15A1.5 1.5 0 0 1 7 16h18a1.5 1.5 0 0 1-1.5 1.5");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vn4n3no1s {
  stop-color: var(--svg-color--9f5e0f, #9F5E0F);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.xv_ozxxod {
  d: path("M9.447 13.89a1 1 0 1 1-.894-1.789l2.206-1.103H14a1 1 0 0 1-.553.892z");
}

.z-xmlwmhd {
  stop-color: var(--svg-color--f08b13, #F08B13);
  stop-opacity: 0;
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
