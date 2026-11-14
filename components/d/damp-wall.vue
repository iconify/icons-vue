<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q-0gsvb9v"/><path class="oqfk4sblx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:damp-wall" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oqfk4sblx {
  d: path("M8 14s-1.75 2.25-1.75 3.5a1.75 1.75 0 0 0 3.5 0C9.75 16.25 8 14 8 14m7.5 0s-1.75 2.25-1.75 3.5a1.75 1.75 0 0 0 3.5 0c0-1.25-1.75-3.5-1.75-3.5");
}

.q-0gsvb9v {
  d: path("M4.25 2.5h15.5a1.75 1.75 0 0 1 1.75 1.75v15.5a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75V4.25A1.75 1.75 0 0 1 4.25 2.5M2.5 7h19m-19 4.5h19M9 2.5V7m6.5-4.5V7m-10 0v4.5M12 7v4.5M18.5 7v4.5");
}

</style>
