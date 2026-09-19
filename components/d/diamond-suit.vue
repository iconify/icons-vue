<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ibAxpcc)"><path fill="url(#iepAShc)" class="cgop9j30r"/></g><defs><linearGradient id="iepAShc" x1="16" x2="16" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="tkug1h3_s"/><stop offset="1" class="pnkyxbl9w"/></linearGradient><filter id="ibAxpcc" width="26.5" height="28" x="2.75" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.219608 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4043"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.380392 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4043" result="effect2_innerShadow_18_4043"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:diamond-suit" /></template>
<style>
.cgop9j30r {
  d: path("M14.378 2.772L4.523 14.555a2.27 2.27 0 0 0 0 2.898l9.855 11.782a2.102 2.102 0 0 0 3.244 0l9.855-11.782a2.27 2.27 0 0 0 0-2.898L17.622 2.772a2.09 2.09 0 0 0-3.244 0");
}

.ft5dv1b6b {
  fill: none;
}

.pnkyxbl9w {
  stop-color: var(--svg-color--fd3da2, #FD3DA2);
}

.tkug1h3_s {
  stop-color: var(--svg-color--ff3f64, #FF3F64);
}

</style>
