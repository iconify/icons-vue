<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e0uu6ccdd"/><path class="hcph2vszz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bear-head" /></template>
<style>
.e0uu6ccdd {
  d: path("M4 12.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0");
}

.hcph2vszz {
  d: path("M5 8.5A2.75 2.75 0 1 1 9.25 5m5.5 0A2.75 2.75 0 1 1 19 8.5M8.25 15a3.75 2.5 0 1 0 7.5 0a3.75 2.5 0 1 0-7.5 0M12 14h.01M8.5 10h.01m6.99 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
