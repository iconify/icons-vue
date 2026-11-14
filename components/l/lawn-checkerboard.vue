<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ytycny5mn"/><path class="f67yay2kc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lawn-checkerboard" /></template>
<style>
.f67yay2kc {
  fill: currentColor;
  d: path("M7.671 4.5H10.5A1.5 1.5 0 0 1 12 6v4a1.5 1.5 0 0 1-1.5 1.5H6.671a1.5 1.5 0 0 1-1.455-1.864l1-4A1.5 1.5 0 0 1 7.671 4.5m5.829 7h4.614a1.5 1.5 0 0 1 1.444 1.094l1.406 5A1.5 1.5 0 0 1 19.52 19.5H13.5A1.5 1.5 0 0 1 12 18v-5a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ytycny5mn {
  d: path("M6.5 4.5h11l4 15h-19Z");
}

</style>
