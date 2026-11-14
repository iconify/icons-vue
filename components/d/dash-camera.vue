<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rm9n4ib9j"/><path class="a_46kl5vf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dash-camera" /></template>
<style>
.a_46kl5vf {
  d: path("M11.5 13.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rm9n4ib9j {
  d: path("M2.5 5q9.5-3 19 0M12 3.5v4m-4.625 0h9.25A4.375 4.375 0 0 1 21 11.875v2.75A4.375 4.375 0 0 1 16.625 19h-9.25A4.375 4.375 0 0 1 3 14.625v-2.75A4.375 4.375 0 0 1 7.375 7.5");
}

</style>
