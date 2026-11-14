<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fjvtn9w9u"/><path class="zcqhsvbel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coverage-indoor" /></template>
<style>
.fjvtn9w9u {
  d: path("M3 17.875v-6.591a2.63 2.63 0 0 1 1.013-2.072l6.375-4.959a2.625 2.625 0 0 1 3.224 0l6.375 4.959A2.63 2.63 0 0 1 21 11.284v6.591a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 17.875M12 17h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zcqhsvbel {
  d: path("M9.525 14.525a3.5 3.5 0 0 1 4.95 0m-7.071-2.121a6.5 6.5 0 0 1 9.192 0");
}

</style>
