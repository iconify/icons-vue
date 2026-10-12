<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="msx4mwb6m"/><path class="ubxws5w8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:follower-count" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.msx4mwb6m {
  cx: 8px;
  cy: 7px;
  r: 3.25px;
}

.ubxws5w8x {
  d: path("M2.75 19.5a5.25 5.25 0 0 1 10.5 0a.75.75 0 0 1-.75.75h-9a.75.75 0 0 1-.75-.75m13 .75v-3m2.75 3v-6.5m2.75 6.5v-10");
}

</style>
