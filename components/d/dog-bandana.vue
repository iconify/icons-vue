<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hus8e815m"/><path class="gqs7ae1cz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dog-bandana" /></template>
<style>
.gqs7ae1cz {
  d: path("M3 13.5L5 15h14l2-1.5M5 15l6 5.75q1 .75 2 0L19 15m-9-6.5h.01m3.99 0h.01m-2.01 3h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hus8e815m {
  d: path("M7 7a5 5 0 0 1 10 0v4a5 4 0 0 1-10 0Zm0-2c-3-.5-4.5 1.5-4 5c2 0 3.5-1 4-2m10-3c3-.5 4.5 1.5 4 5c-2 0-3.5-1-4-2");
}

</style>
