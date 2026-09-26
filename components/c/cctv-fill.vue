<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="qx95zxwhr"/><path class="m65_b2bky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cctv-fill" /></template>
<style>
.m65_b2bky {
  d: path("M17.0742 8.3718L19.9192 8.1446C20.6602 8.0854 21.2044 8.8268 20.926 9.516L19.516 13.0059C19.2375 13.6951 18.331 13.8504 17.8391 13.293L15.9503 11.1533M7.3201 9.8235L7.3201 17L3 17M3 13L3 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qx95zxwhr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.8533 2.2187L17.2708 5.2156C18.0267 5.521 18.5216 6.2547 18.5216 7.07C18.5216 7.3267 18.4721 7.5811 18.3759 7.8192L16.5029 12.4551C16.1975 13.211 15.4638 13.7059 14.6485 13.7059C14.3918 13.7059 14.1374 13.6564 13.8993 13.5603L6.4819 10.5634C5.348 10.1053 4.6057 9.0048 4.6057 7.7818C4.6057 7.3967 4.6798 7.0151 4.8241 6.658L5.9479 3.8765C6.4061 2.7426 7.5066 2.0003 8.7295 2.0003C9.1147 2.0003 9.4962 2.0745 9.8533 2.2187Z");
  stroke: none;
}

</style>
