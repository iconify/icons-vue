<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l3hqozy6b"/><path class="n1t9fdc6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drain-snake" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3hqozy6b {
  d: path("M3 10a7 7 0 1 0 14 0a7 7 0 1 0-14 0m14 0h4V6");
}

.n1t9fdc6s {
  d: path("M10 17q0 4 4 4h3.5q2.5 0 3-2.5M7.5 10a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
