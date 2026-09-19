<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i28l3ie)" class="z-23ntbax"/><path fill="url(#iibyWNb)" class="tgax6nbbn"/><path fill="url(#iDHxldz)" class="tgax6nbbn"/><path fill="url(#iwIKlle)" class="fzsf86_nq"/><path fill="url(#i0ULSxc)" class="fzsf86_nq"/><path fill="url(#i2sRV4w)" class="x93-1ibvc"/><path fill="url(#iA9aQqd)" class="x93-1ibvc"/><path fill="url(#iCooGfd)" class="lh9e82bmc"/><path fill="url(#iCBfD0l)" class="lh9e82bmc"/><g filter="url(#iVXoMlb)"><path fill="url(#iKwEc1b)" class="aqpcs98yu"/><path fill="url(#i65fDhe)" class="aqpcs98yu"/><path fill="url(#iXxJgwd)" class="aqpcs98yu"/></g><path fill="url(#iD6tOEe)" class="aqpcs98yu"/><path fill="url(#iSQQeQd)" class="bx8c0t0kb"/><g filter="url(#iIGaitv)"><path stroke="url(#isW7F1J)" class="v2333dcrw"/></g><defs><linearGradient id="i28l3ie" x1="16.808" x2="14.997" y1="23.288" y2="25" gradientUnits="userSpaceOnUse"><stop class="ktms3i-dy"/><stop offset="1" class="w0tpm7zrt"/></linearGradient><linearGradient id="iibyWNb" x1="17" x2="15.344" y1="5.88" y2="7.505" gradientUnits="userSpaceOnUse"><stop class="reaauhb2o"/><stop offset="1" class="sae6l9brz"/></linearGradient><linearGradient id="iDHxldz" x1="15" x2="15.781" y1="6.161" y2="6.161" gradientUnits="userSpaceOnUse"><stop class="yyt7jmb3d"/><stop offset="1" class="d75ev1bkc"/></linearGradient><linearGradient id="i0ULSxc" x1="16.75" x2="16.75" y1="6.161" y2="5.505" gradientUnits="userSpaceOnUse"><stop class="zg4tki8sx"/><stop offset="1" class="napztkbla"/></linearGradient><linearGradient id="iA9aQqd" x1="15.68" x2="15.916" y1="26.217" y2="28.65" gradientUnits="userSpaceOnUse"><stop class="ncch-us7t"/><stop offset="1" class="pc9ny7w7d"/></linearGradient><linearGradient id="iCBfD0l" x1="15.726" x2="16" y1="24.217" y2="26.642" gradientUnits="userSpaceOnUse"><stop class="ncch-us7t"/><stop offset="1" class="pc9ny7w7d"/></linearGradient><linearGradient id="iXxJgwd" x1="16" x2="16" y1="23.317" y2="21.817" gradientUnits="userSpaceOnUse"><stop class="xjpluye0g"/><stop offset="1" class="jtekjmg7f"/></linearGradient><linearGradient id="isW7F1J" x1="25.063" x2="5.938" y1="21.005" y2="21.005" gradientUnits="userSpaceOnUse"><stop class="zggj_7mss"/><stop offset="1" class="h_a65i7jg"/></linearGradient><radialGradient id="iwIKlle" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.4018 -5.47737 0 17.501 4.598)" gradientUnits="userSpaceOnUse"><stop class="gkaxbebhv"/><stop offset="1" class="su0p4ybtt"/></radialGradient><radialGradient id="i2sRV4w" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.69215 -23.6902 0 22.052 28)" gradientUnits="userSpaceOnUse"><stop class="tz0-tcc3l"/><stop offset="1" class="ymd5_bbse"/></radialGradient><radialGradient id="iCooGfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.69215 -20.3058 0 21.188 26)" gradientUnits="userSpaceOnUse"><stop class="tz0-tcc3l"/><stop offset="1" class="ymd5_bbse"/></radialGradient><radialGradient id="iKwEc1b" cx="0" cy="0" r="1" gradientTransform="rotate(-46.668 32.961 -.904)scale(18.2157 30.1442)" gradientUnits="userSpaceOnUse"><stop class="qw5ikl4hz"/><stop offset="1" class="c-ol6fbce"/></radialGradient><radialGradient id="i65fDhe" cx="0" cy="0" r="1" gradientTransform="matrix(26.00002 16.9375 -29.6406 45.5 2 5.692)" gradientUnits="userSpaceOnUse"><stop offset=".832" class="g5vjrzd2z"/><stop offset="1" class="em0us0bgn"/></radialGradient><radialGradient id="iD6tOEe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.77717 10.57178 -12.3303 -10.23717 25.464 7)" gradientUnits="userSpaceOnUse"><stop class="xh-l_dm2h"/><stop offset="1" class="x1d3yybnf"/></radialGradient><radialGradient id="iSQQeQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40624 -4.37966 7.28568 -2.33932 20.719 13.38)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="bxfv9slxn"/><stop offset="1" class="dkpy53unb"/></radialGradient><filter id="iVXoMlb" width="29" height="16" x="2" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.439216 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13152"/></filter><filter id="iIGaitv" width="24.538" height="1.6" x="3.794" y="19.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13152" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bellhop-bell" /></template>
<style>
.aqpcs98yu {
  d: path("M27.97 20.059v-.67c0-6.604-5.157-12.267-11.755-12.387c-6.718-.12-12.206 5.293-12.206 11.986v1A1.007 1.007 0 0 1 3 21c-.55 0-.999.45-.999 1S2.45 23 3 23h26c.55 0 1-.45 1-1s-.45-1.001-1-1.001h-.07a.93.93 0 0 1-.96-.94");
}

.bx8c0t0kb {
  d: path("M19.98 13a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.bxfv9slxn {
  stop-color: var(--svg-color--fffff7, #FFFFF7);
  stop-opacity: 0;
}

.c-ol6fbce {
  stop-color: var(--svg-color--ffc551, #FFC551);
}

.d75ev1bkc {
  stop-color: var(--svg-color--cf814b, #CF814B);
  stop-opacity: 0;
}

.dkpy53unb {
  stop-color: var(--svg-color--fffff7, #FFFFF7);
}

.em0us0bgn {
  stop-color: var(--svg-color--ffa74f, #FFA74F);
}

.ft5dv1b6b {
  fill: none;
}

.fzsf86_nq {
  d: path("M14.003 4h3.994C18.549 4 19 4.45 19 5s-.451 1-1.003 1h-3.994C13.451 6 13 5.55 13 5s.451-1 1.003-1");
}

.g5vjrzd2z {
  stop-color: var(--svg-color--ffa74f, #FFA74F);
  stop-opacity: 0;
}

.gkaxbebhv {
  stop-color: var(--svg-color--ffb45d, #FFB45D);
}

.h_a65i7jg {
  stop-color: var(--svg-color--d57425, #D57425);
}

.jtekjmg7f {
  stop-color: var(--svg-color--ea6733, #EA6733);
  stop-opacity: 0;
}

.ktms3i-dy {
  stop-color: var(--svg-color--893313, #893313);
}

.lh9e82bmc {
  d: path("M28 27H4c0-1.1.9-2 2-2h20a2 2 0 0 1 2 2");
}

.napztkbla {
  stop-color: var(--svg-color--e5680c, #E5680C);
  stop-opacity: 0;
}

.ncch-us7t {
  stop-color: var(--svg-color--6d2f20, #6D2F20);
}

.pc9ny7w7d {
  stop-color: var(--svg-color--6d2f20, #6D2F20);
  stop-opacity: 0;
}

.qw5ikl4hz {
  stop-color: var(--svg-color--da7d35, #DA7D35);
}

.reaauhb2o {
  stop-color: var(--svg-color--f17523, #F17523);
}

.sae6l9brz {
  stop-color: var(--svg-color--de7c26, #DE7C26);
}

.su0p4ybtt {
  stop-color: var(--svg-color--dd7b36, #DD7B36);
}

.tgax6nbbn {
  d: path("M15 8.053V4.947c0-.52.45-.947 1-.947s1 .426 1 .947v3.106c0 .52-.45.947-1 .947s-1-.426-1-.947");
}

.tz0-tcc3l {
  stop-color: var(--svg-color--9d7467, #9D7467);
}

.v2333dcrw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M4.594 20.63H27.53");
}

.w0tpm7zrt {
  stop-color: var(--svg-color--944c20, #944C20);
}

.x1d3yybnf {
  stop-color: var(--svg-color--ffc455, #FFC455);
  stop-opacity: 0;
}

.x93-1ibvc {
  d: path("M30 29H2c0-1.1.901-2 2.002-2h23.996c1.101 0 2.002.9 2.002 2");
}

.xh-l_dm2h {
  stop-color: var(--svg-color--ffc455, #FFC455);
}

.xjpluye0g {
  stop-color: var(--svg-color--ea6733, #EA6733);
}

.ymd5_bbse {
  stop-color: var(--svg-color--664a42, #664A42);
}

.yyt7jmb3d {
  stop-color: var(--svg-color--cf814b, #CF814B);
}

.z-23ntbax {
  d: path("M18 22h-4v3h4z");
}

.zg4tki8sx {
  stop-color: var(--svg-color--e5680c, #E5680C);
}

.zggj_7mss {
  stop-color: var(--svg-color--ff932e, #FF932E);
}

</style>
