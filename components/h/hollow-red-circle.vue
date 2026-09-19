<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ifyQSve)"><circle stroke="url(#i7E9xGb)" class="h--s0w25k"/></g><g filter="url(#iB3CONd)"><circle stroke="url(#imLaB1c)" class="fs56ii-fc"/><circle stroke="url(#i7QsBif)" class="fs56ii-fc"/></g><defs><linearGradient id="i7E9xGb" x1="23.438" x2="6.688" y1="3.875" y2="22.875" gradientUnits="userSpaceOnUse"><stop class="xv0w7-1_v"/><stop offset=".486" class="v1i9l_34y"/><stop offset="1" class="pnfptebpm"/></linearGradient><linearGradient id="imLaB1c" x1="26.598" x2="16.305" y1="5.422" y2="19.179" gradientUnits="userSpaceOnUse"><stop class="tgtxogbrq"/><stop offset="1" class="p6ig2wjuq"/></linearGradient><linearGradient id="i7QsBif" x1="7.388" x2="12.589" y1="23.29" y2="17.25" gradientUnits="userSpaceOnUse"><stop class="lv2uh3b6h"/><stop offset="1" class="j08oxsjgd"/></linearGradient><filter id="ifyQSve" width="28.375" height="28.375" x="2.032" y="1.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.164706 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1981"/></filter><filter id="iB3CONd" width="27.375" height="27.375" x="2.617" y="1.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1981" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:hollow-red-circle" /></template>
<style>
.fs56ii-fc {
  cx: 16.305px;
  cy: 15.414px;
  r: 12.438px;
}

.ft5dv1b6b {
  fill: none;
}

.h--s0w25k {
  cx: 15.969px;
  cy: 15.75px;
  r: 12.438px;
  stroke-width: var(--svg-stroke-width--3px, 3px);
}

.j08oxsjgd {
  stop-color: var(--svg-color--ff6d6f, #FF6D6F);
  stop-opacity: 0;
}

.lv2uh3b6h {
  stop-color: var(--svg-color--ff6d6f, #FF6D6F);
}

.p6ig2wjuq {
  stop-color: var(--svg-color--ff75a8, #FF75A8);
  stop-opacity: 0;
}

.pnfptebpm {
  stop-color: var(--svg-color--ef3741, #EF3741);
}

.tgtxogbrq {
  stop-color: var(--svg-color--ff75a8, #FF75A8);
}

.v1i9l_34y {
  stop-color: var(--svg-color--db3051, #DB3051);
}

.xv0w7-1_v {
  stop-color: var(--svg-color--ff5c96, #FF5C96);
}

</style>
