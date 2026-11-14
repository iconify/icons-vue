<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fddcqdb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deep-space-network" /></template>
<style>
.fddcqdb7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8C3.5 14 9 19.5 15 19.5ZM7 16v5.5m-3 0h6m-.75-7.75l3.25-3.25m.906-3.381a3.5 3.5 0 0 1 2.475 2.475m-2.165-5.988a7 7 0 0 1 5.678 5.678");
}

</style>
