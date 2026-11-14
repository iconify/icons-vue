<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gsb9mz74h"/><path class="d5vr6fday"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:csv-table" /></template>
<style>
.d5vr6fday {
  d: path("M15.5 2.5v4a2 2 0 0 0 2 2h4M8 12.75a2.75 2.75 0 1 0 0 4.5m5.5-4.5Q12.9 12 12 12c-.9 0-1.5.5-1.5 1.25c0 1.5 3 1 3 2.75c0 .9-.6 1.5-1.5 1.5q-.9 0-1.5-.75m5-4.75l1.75 5.5L19 12");
}

.gsb9mz74h {
  d: path("M5 2.5h10.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H5A2.5 2.5 0 0 1 2.5 19V5A2.5 2.5 0 0 1 5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
