<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iJOUKwe)"><path fill="url(#i9JhlUd)" class="uxgsmd1pz"/></g><defs><linearGradient id="i9JhlUd" x1="16" x2="16" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="tltvubccb"/><stop offset="1" class="klludvaaf"/></linearGradient><filter id="iJOUKwe" width="30" height="29" x="1" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.333333 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3194"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3194" result="effect2_innerShadow_18590_3194"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.364706 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_3194" result="effect3_innerShadow_18590_3194"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:blue-square" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.klludvaaf {
  stop-color: var(--svg-color--4273d3, #4273D3);
}

.tltvubccb {
  stop-color: var(--svg-color--3e8cd9, #3E8CD9);
}

.uxgsmd1pz {
  d: path("M2 4a2 2 0 0 1 2-2h24a2 2 0 0 1 2 2v24a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2z");
}

</style>
