<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lcjhqeb2x"/><path class="j_6i03sve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-seat-child" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_6i03sve {
  d: path("M9 16.5h10l-2.5-7.75");
}

.lcjhqeb2x {
  d: path("M4 16.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0m12.5-7.75H4.25A1.25 1.25 0 0 1 3 7.5V3.75A1.25 1.25 0 0 1 4.25 2.5H5a1.25 1.25 0 0 1 1.25 1.25v2H11A1.25 1.25 0 0 1 12.25 7v1.75");
}

</style>
