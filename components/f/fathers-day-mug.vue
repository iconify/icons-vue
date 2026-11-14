<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zo1wmq8rx"/><path class="rrq7p2c6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fathers-day-mug" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rrq7p2c6s {
  d: path("M8.75 5h2.5l-.5 2.5l1.5 6.5L10 16.5L7.75 14l1.5-6.5Z");
}

.zo1wmq8rx {
  d: path("M3.5 5h13v11a4 4 0 0 1-4 4h-5a4 4 0 0 1-4-4Zm13 3h1.25a3 3 0 0 1 0 6H16.5");
}

</style>
