<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ldpwh2zvp"/><path class="cva4px-rf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:holiday-cottage" /></template>
<style>
.cva4px-rf {
  d: path("M5.5 21.5v-5h3v5m4.25-6.5za1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5M16 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldpwh2zvp {
  d: path("m3.082 12.478l5.5-4.931a1.75 1.75 0 0 1 2.336 0l5.5 4.931A1.75 1.75 0 0 1 17 13.781v5.969a1.75 1.75 0 0 1-1.75 1.75h-11a1.75 1.75 0 0 1-1.75-1.75v-5.969a1.75 1.75 0 0 1 .582-1.303");
}

</style>
