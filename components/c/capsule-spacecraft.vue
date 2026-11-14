<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qagvjbc0e"/><path class="i0kvlvwbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:capsule-spacecraft" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i0kvlvwbh {
  d: path("M9.75 11.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.qagvjbc0e {
  d: path("M10.765 4.5h2.47a2.625 2.625 0 0 1 2.431 1.635l3.361 8.25A2.625 2.625 0 0 1 16.596 18H7.404a2.625 2.625 0 0 1-2.431-3.615l3.361-8.25A2.625 2.625 0 0 1 10.765 4.5M5 20.75h14");
}

</style>
