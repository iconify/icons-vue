<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nr49f5bso"/><path class="schs_svoz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-emergency-cover" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr49f5bso {
  d: path("M3.365 9.718L8.49 5.089a2.625 2.625 0 0 1 3.52 0l5.125 4.629A2.63 2.63 0 0 1 18 11.666v6.209a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 17.875v-6.209a2.63 2.63 0 0 1 .865-1.948");
}

.schs_svoz {
  d: path("M7.75 20.5v-5h5v5m8.25-8v5m0 3.5h.01");
}

</style>
