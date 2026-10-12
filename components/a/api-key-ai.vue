<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="nr14crr6d"/><path class="pvvit4b0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:api-key-ai" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr14crr6d {
  cx: 7.75px;
  cy: 16.25px;
  r: 5px;
}

.pvvit4b0i {
  d: path("m11.3 12.7l8.45-8.45M17 7l2.5 2.5m.25-5.25l1.5 1.5M7.75 13.5q.33 2.42 2.75 2.75q-2.42.33-2.75 2.75q-.33-2.42-2.75-2.75q2.42-.33 2.75-2.75");
}

</style>
