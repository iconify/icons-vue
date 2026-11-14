<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bhbljxb-f"/><path class="azxliubhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-filling" /></template>
<style>
.azxliubhu {
  d: path("M11 7.25h2a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5");
}

.bhbljxb-f {
  d: path("M5 3.5C3 3.5 3 6 3.5 9s2 4.5 2.5 6l1.5 5c.5 1 1.5.5 1.75-.5l1.25-5h3l1.25 5c.25 1 1.25 1.5 1.75.5l1.5-5c.5-1.5 2-3 2.5-6S21 3.5 19 3.5c-2.5 0-4 1-7 1s-4.5-1-7-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
