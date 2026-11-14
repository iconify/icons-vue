<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi83sr6ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deserialization" /></template>
<style>
.oi83sr6ho {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 4a1.25 1.25 0 0 0-1.25 1.25v5.25l-1 1.5l1 1.5v5.25A1.25 1.25 0 0 0 16.5 20m2.75-16a1.25 1.25 0 0 1 1.25 1.25v5.25l1 1.5l-1 1.5v5.25A1.25 1.25 0 0 1 19.25 20M4 4h.5A1.5 1.5 0 0 1 6 5.5V6a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 6v-.5A1.5 1.5 0 0 1 4 4m0 6.25h.5a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5H4a1.5 1.5 0 0 1-1.5-1.5v-.5a1.5 1.5 0 0 1 1.5-1.5m0 6.25h.5A1.5 1.5 0 0 1 6 18v.5A1.5 1.5 0 0 1 4.5 20H4a1.5 1.5 0 0 1-1.5-1.5V18A1.5 1.5 0 0 1 4 16.5m5-7l2.5 2.5L9 14.5");
}

</style>
