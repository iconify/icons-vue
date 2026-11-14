<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eyhrnt-2v"/><path class="a6q03syge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:engaged-couple" /></template>
<style>
.a6q03syge {
  d: path("M10.164 3h3.672a1.5 1.5 0 0 1 1.11.491l.867.954a1.5 1.5 0 0 1-.292 2.266l-2.704 1.758a1.5 1.5 0 0 1-1.634 0L8.479 6.711a1.5 1.5 0 0 1-.292-2.266l.867-.954A1.5 1.5 0 0 1 10.164 3M7 5.75h10");
}

.eyhrnt-2v {
  d: path("M6 15a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
