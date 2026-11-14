<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ocsc7rb0u"/><path class="wtuzlnibj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cow-head" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ocsc7rb0u {
  d: path("M7 14.75V11.5H3.5l1.5-3h2a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2h2l1.5 3H17v3.25");
}

.wtuzlnibj {
  d: path("M6 17a6 4 0 1 0 12 0a6 4 0 1 0-12 0M8.5 6.5c-1.5-.5-3-2-3-4m10 4c1.5-.5 3-2 3-4M9.75 10h.01m4.49 0h.01");
}

</style>
