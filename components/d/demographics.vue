<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aaviccc8y"/><path class="ygrt6eb5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:demographics" /></template>
<style>
.aaviccc8y {
  d: path("M9.25 8a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M6.5 20c0-3.5 2.5-5.75 5.5-5.75q.29 0 .573.028M2.5 6.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m0 8.5c0-2.5 1-4 2.5-4c.75 0 1.5.25 2 .75M17 6.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M14.25 18a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ygrt6eb5m {
  d: path("M18 14.25V18h3.75");
}

</style>
