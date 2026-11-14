<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gknmrxhpc"/><path class="zzuba7bqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:invoice-print" /></template>
<style>
.gknmrxhpc {
  d: path("M2.5 4h19v10h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zzuba7bqg {
  d: path("M7.5 10.5v10h9v-10M6 10.5h12M10.25 17h3.5M18 7h.01");
}

</style>
