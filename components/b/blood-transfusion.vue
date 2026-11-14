<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dcp7fe0vl"/><path class="rci6-rnvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blood-transfusion" /></template>
<style>
.dcp7fe0vl {
  d: path("M7 3.25h2a3.5 3.5 0 0 1 3.5 3.5v3.5a3.5 3.5 0 0 1-3.5 3.5H7a3.5 3.5 0 0 1-3.5-3.5v-3.5A3.5 3.5 0 0 1 7 3.25m1 10.5c0 5 4 2.5 7.5 7m-4.5 0h10.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rci6-rnvh {
  d: path("M8 6.25c1.5 1.75 1.75 2.5 1.75 3a1.75 1.75 0 0 1-3.5 0c0-.5.25-1.25 1.75-3");
}

</style>
