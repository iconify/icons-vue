<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akhc4dbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-box-plot" /></template>
<style>
.akhc4dbhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 4v4.5m-3 0h6v7h-6Zm3 7V20m9-16v2.5m-3 0h6v6h-6Zm3 6V17m-12-5h6m3-2h6");
}

</style>
