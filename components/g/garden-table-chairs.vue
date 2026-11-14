<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqkxt6lyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-table-chairs" /></template>
<style>
.oqkxt6lyo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 10.5a5 1.5 0 1 0 10 0a5 1.5 0 1 0-10 0Zm5 1.5v8.5m-2 0h4M3.5 6v14.5m0-6.5h4v6.5M20.5 6v14.5m0-6.5h-4v6.5");
}

</style>
