<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="upec2cc0q"/><path class="myk85bb5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:doorbell-camera-motion" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.myk85bb5z {
  d: path("M6 7.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.25 8a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M16.5 3a9.75 9.75 0 0 1 0 9m3.25-10a13 13 0 0 1 0 11");
}

.upec2cc0q {
  d: path("M8 2.5za5 5 0 0 1 5 5v9a5 5 0 0 1-5 5a5 5 0 0 1-5-5v-9a5 5 0 0 1 5-5");
}

</style>
