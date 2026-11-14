<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pag5k6upz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheque-print" /></template>
<style>
.pag5k6upz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5h19v8h-19Zm4 0v-3a1 1 0 0 1 1-1h9a1 1 0 0 1 1 1v3m-12 8v6a1 1 0 0 0 1 1h11a1 1 0 0 0 1-1v-6m-10 3.25h4M18 10.5h.01");
}

</style>
