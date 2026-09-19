<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHoZ1Sd)"><path fill="url(#i5qgeEe)" class="uxgsmd1pz"/></g><defs><linearGradient id="i5qgeEe" x1="16" x2="16" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="mf78xacle"/><stop offset="1" class="wxek4j95m"/></linearGradient><filter id="iHoZ1Sd" width="30" height="30" x="1" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.176471 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3246"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.454902 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3246" result="effect2_innerShadow_18590_3246"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.207843 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_3246" result="effect3_innerShadow_18590_3246"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.392157 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18590_3246" result="effect4_innerShadow_18590_3246"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:brown-square" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mf78xacle {
  stop-color: var(--svg-color--925e5d, #925E5D);
}

.uxgsmd1pz {
  d: path("M2 4a2 2 0 0 1 2-2h24a2 2 0 0 1 2 2v24a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2z");
}

.wxek4j95m {
  stop-color: var(--svg-color--6f4553, #6F4553);
}

</style>
