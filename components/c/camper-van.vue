<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ori92kbya"/><path class="dmr5qtkxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camper-van" /></template>
<style>
.dmr5qtkxf {
  d: path("M13 7.5V12h7M5 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ori92kbya {
  d: path("M2.5 15.5v-6a2 2 0 0 1 2-2h10.75c.75 0 1.25.25 1.75 1l3.75 3.5c.5.5.75 1 .75 1.75v1.75A1.5 1.5 0 0 1 20 17H4a1.5 1.5 0 0 1-1.5-1.5m2-8l1.25-4H13l1.25 4");
}

</style>
