<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wjtosw_9o"/><path class="ssic-rbxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hobby-time" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ssic-rbxl {
  d: path("M17 8.5L15.5 7l-2.25 2.25C12.25 10.25 12 12 12 12s1.75-.25 2.75-1.25Z");
}

.wjtosw_9o {
  d: path("M16.218 3.861A10.8 10.8 0 0 0 12 3c-5.5 0-9.5 4-9.5 9s4 9 8.5 9c1.5 0 2-1 1.5-2.5s.5-3 2-3H17c2.5 0 4.5-2 4.5-4.5a6.84 6.84 0 0 0-.979-3.504M7.5 9h.01M8 14.5h.01M21 3l-4.75 4.75");
}

</style>
