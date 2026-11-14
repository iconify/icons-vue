<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p5svho3ut"/><path class="p8-4cab4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-baseline" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p5svho3ut {
  fill: currentColor;
  d: path("M3.5 11h17a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1a1 1 0 0 1 1-1");
}

.p8-4cab4c {
  d: path("M2.5 8c3-5.5 6-5.5 7.5 0s2.5 13.5 5.5 13.5s4-5.5 6-6.5");
}

</style>
