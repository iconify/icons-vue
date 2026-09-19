<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ihz9FvI)"><rect fill="url(#iq3jNei)" class="uglwsybcv"/></g><g filter="url(#imw7Rie)"><rect fill="url(#iwUepae)" class="r6smxcc4g"/></g><defs><linearGradient id="iq3jNei" x1="16.126" x2="16.126" y1="2.295" y2="29.886" gradientUnits="userSpaceOnUse"><stop class="rkcmnr2pa"/><stop offset="1" class="a0j4e18ua"/></linearGradient><linearGradient id="iwUepae" x1="16.125" x2="16.125" y1="8.191" y2="26.607" gradientUnits="userSpaceOnUse"><stop class="ly5meghmu"/><stop offset="1" class="m7kk8ob_d"/></linearGradient><filter id="ihz9FvI" width="29.771" height="28.771" x="1.365" y="1.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.2 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2969"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.54902 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2969" result="effect2_innerShadow_18590_2969"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.368627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_2969" result="effect3_innerShadow_18590_2969"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.219608 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18590_2969" result="effect4_innerShadow_18590_2969"/></filter><filter id="imw7Rie" width="22.463" height="22.613" x="4.644" y="4.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.14902 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18590_2969"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18590_2969" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.937255 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18590_2969"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.886275 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_2969" result="effect3_innerShadow_18590_2969"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.521569 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18590_2969" result="effect4_innerShadow_18590_2969"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:black-square-button" /></template>
<style>
.a0j4e18ua {
  stop-color: var(--svg-color--423551, #423551);
}

.ft5dv1b6b {
  fill: none;
}

.ly5meghmu {
  stop-color: var(--svg-color--f3e7ff, #F3E7FF);
}

.m7kk8ob_d {
  stop-color: var(--svg-color--c3abdb, #C3ABDB);
}

.r6smxcc4g {
  width: 21.463px;
  height: 21.463px;
  x: 5.394px;
  y: 5.144px;
  rx: 0.5px;
}

.rkcmnr2pa {
  stop-color: var(--svg-color--58456d, #58456D);
}

.uglwsybcv {
  width: 28.021px;
  height: 28.021px;
  x: 2.115px;
  y: 1.864px;
  rx: 2px;
}

</style>
