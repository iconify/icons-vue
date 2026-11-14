<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xm3rkgbst"/><path class="zzuba7bqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:invoice-print" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xm3rkgbst {
  d: path("M6 4h12a3.5 3.5 0 0 1 3.5 3.5v3A3.5 3.5 0 0 1 18 14H6a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 6 4");
}

.zzuba7bqg {
  d: path("M7.5 10.5v10h9v-10M6 10.5h12M10.25 17h3.5M18 7h.01");
}

</style>
