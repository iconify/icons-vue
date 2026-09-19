<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ibWwE0c)"><path fill="url(#iN6wjze)" class="uxgsmd1pz"/></g><defs><linearGradient id="iN6wjze" x1="16" x2="16" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="j11uswbxt"/><stop offset="1" class="hgr9_0sdz"/></linearGradient><filter id="ibWwE0c" width="30" height="28.75" x="1" y="1.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.564706 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3168"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.94902 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3168" result="effect2_innerShadow_18590_3168"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.627451 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_3168" result="effect3_innerShadow_18590_3168"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:green-square" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hgr9_0sdz {
  stop-color: var(--svg-color--3fb180, #3FB180);
}

.j11uswbxt {
  stop-color: var(--svg-color--55d894, #55D894);
}

.uxgsmd1pz {
  d: path("M2 4a2 2 0 0 1 2-2h24a2 2 0 0 1 2 2v24a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2z");
}

</style>
