<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tj591xb5k"/><path class="fukuw3b5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cottage" /></template>
<style>
.fukuw3b5d {
  d: path("M10 21.5v-4a2 2 0 0 1 4 0v4m-8-11c2-1 10-1 12 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tj591xb5k {
  d: path("M2.5 13c0-2 1-3.5 2.5-4.5L10 4c1.25-1 2.75-1 4 0l5 4.5c1.5 1 2.5 2.5 2.5 4.5ZM5 13v8.5h14V13");
}

</style>
