<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r5659k6od"/><path class="x0m_cmolk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:earth-leaf" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r5659k6od {
  d: path("M2.5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

.x0m_cmolk {
  d: path("M6.5 9.5a3 7 0 1 0 6 0a3 7 0 1 0-6 0m-4 0h14M16 20c0-3.5 1.5-5 5-5c0 3.5-1.5 5-5 5m0 0l-1.25 1.25");
}

</style>
