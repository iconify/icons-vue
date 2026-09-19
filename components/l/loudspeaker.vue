<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#ib9mGNd)" class="lgkkmnb0n"/><circle fill="url(#ighq4ib)" class="lgkkmnb0n"/><path fill="url(#iQuu2Kb)" class="fjxuplbxv"/><path fill="url(#irNdrqP)" class="fjxuplbxv"/><g filter="url(#iFiBMvc)"><path fill="url(#iNXw0Ob)" class="lytrs6b9u"/></g><g filter="url(#iTaMYxh)"><path fill="url(#iNEFHrb)" class="fdk5k_boe"/></g><g filter="url(#indOVie)"><rect fill="url(#ijhCm2c)" class="mgjt6zbca"/><rect fill="url(#iHlz2ad)" class="mgjt6zbca"/></g><defs><radialGradient id="ib9mGNd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03126 1.49998 -1.4481 -1.96101 29.687 14.665)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="tyqa43byn"/><stop offset="1" class="zxp115b1q"/></radialGradient><radialGradient id="iQuu2Kb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.5 7.23214 0 7.672 28.29)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="rrjkb8e1u"/><stop offset="1" class="iw1ddi-ws"/></radialGradient><radialGradient id="iNEFHrb" cx="0" cy="0" r="1" gradientTransform="matrix(5.875 15.50004 -16.43653 6.22997 13.375 7.415)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="vy8rabbzw"/><stop offset="1" class="j6osju2av"/></radialGradient><radialGradient id="iHlz2ad" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.125 -3.375 0 27 8.54)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="wxn65evnz"/><stop offset="1" class="llg0cqo4j"/></radialGradient><linearGradient id="ighq4ib" x1="27.75" x2="28.25" y1="19.727" y2="16.227" gradientUnits="userSpaceOnUse"><stop offset=".306" class="joc-tpqyv"/><stop offset="1" class="igpg6c5ab"/></linearGradient><linearGradient id="irNdrqP" x1="7.672" x2="7.672" y1="28.821" y2="27.165" gradientUnits="userSpaceOnUse"><stop class="xh8apydiq"/><stop offset="1" class="q5b154cwg"/></linearGradient><linearGradient id="iNXw0Ob" x1="2.562" x2="12.875" y1="17.665" y2="17.665" gradientUnits="userSpaceOnUse"><stop class="urkhpd9de"/><stop offset="1" class="y9qsjukvq"/></linearGradient><linearGradient id="ijhCm2c" x1="24.813" x2="24.813" y1="3.071" y2="28.821" gradientUnits="userSpaceOnUse"><stop class="brvtnrcxi"/><stop offset="1" class="bxzhvabxf"/></linearGradient><filter id="iFiBMvc" width="10.257" height="13.879" x="2.143" y="8.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-2"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.160784 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17873"/></filter><filter id="iTaMYxh" width="11.944" height="23.463" x="12.15" y="2.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-4"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.65098 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17873"/></filter><filter id="indOVie" width="6.625" height="26.75" x="21.75" y="2.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.164706 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17873"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:loudspeaker" /></template>
<style>
.brvtnrcxi {
  stop-color: var(--svg-color--f94e87, #F94E87);
}

.bxzhvabxf {
  stop-color: var(--svg-color--d21f6b, #D21F6B);
}

.fdk5k_boe {
  d: path("M22.219 5.758c-3.203 2-6.516 3.985-10.069 4.297V21.94h.156c3.494.355 6.756 2.31 9.913 4.282l1.132-.154v-4.129a.75.75 0 0 0 .743-.75V10.812a.75.75 0 0 0-.743-.75V5.911z");
}

.fjxuplbxv {
  d: path("M5.25 21.04h4.844v7.28a.5.5 0 0 1-.5.5H5.75a.5.5 0 0 1-.5-.5z");
}

.ft5dv1b6b {
  fill: none;
}

.igpg6c5ab {
  stop-color: var(--svg-color--3a3141, #3A3141);
  stop-opacity: 0;
}

.iw1ddi-ws {
  stop-color: var(--svg-color--b4a0bc, #B4A0BC);
}

.j6osju2av {
  stop-color: var(--svg-color--c1b6d2, #C1B6D2);
}

.joc-tpqyv {
  stop-color: var(--svg-color--3a3141, #3A3141);
}

.lgkkmnb0n {
  cx: 26.281px;
  cy: 15.946px;
  r: 3.781px;
}

.llg0cqo4j {
  stop-color: var(--svg-color--ff4f8a, #FF4F8A);
  stop-opacity: 0;
}

.lytrs6b9u {
  d: path("M2.143 10.81a.75.75 0 0 1 .75-.75h9.257v11.88H2.893a.75.75 0 0 1-.75-.75z");
}

.mgjt6zbca {
  width: 6.125px;
  height: 25.75px;
  x: 21.75px;
  y: 3.071px;
  rx: 3.063px;
}

.q5b154cwg {
  stop-color: var(--svg-color--b5a4d2, #B5A4D2);
  stop-opacity: 0;
}

.rrjkb8e1u {
  stop-color: var(--svg-color--c0b2d4, #C0B2D4);
}

.tyqa43byn {
  stop-color: var(--svg-color--6e6279, #6E6279);
}

.urkhpd9de {
  stop-color: var(--svg-color--f44065, #F44065);
}

.vy8rabbzw {
  stop-color: var(--svg-color--cfccd5, #CFCCD5);
}

.wxn65evnz {
  stop-color: var(--svg-color--ff4f8a, #FF4F8A);
}

.xh8apydiq {
  stop-color: var(--svg-color--b5a4d2, #B5A4D2);
}

.y9qsjukvq {
  stop-color: var(--svg-color--d52e84, #D52E84);
}

.zxp115b1q {
  stop-color: var(--svg-color--5a4c67, #5A4C67);
}

</style>
