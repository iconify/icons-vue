<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3dvh_qtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-legend-sharp" /></template>
<style>
.z3dvh_qtg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v7H2.75zM7 7.25V6m7 1.25V5.5m-3.5 1.75v-2.5m-7.75 8h3v3h-3zm0 5.5h3v3h-3zm6.25-4h8m-8 5.5h5.5");
}

</style>
