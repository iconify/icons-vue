<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="prtsjk3cc"/><path class="zq7_2eptb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:airship" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.prtsjk3cc {
  d: path("M3.5 10a8.5 4.5 0 1 0 17 0a8.5 4.5 0 1 0-17 0");
}

.zq7_2eptb {
  d: path("M11.75 13.5h1.5A1.75 1.75 0 0 1 15 15.25A1.75 1.75 0 0 1 13.25 17h-1.5A1.75 1.75 0 0 1 10 15.25a1.75 1.75 0 0 1 1.75-1.75M4.5 7l-2-2.5m2 8.5l-2 2.5");
}

</style>
