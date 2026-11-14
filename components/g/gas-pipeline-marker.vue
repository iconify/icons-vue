<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eew3bdc7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gas-pipeline-marker" /></template>
<style>
.eew3bdc7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5h5V15h-5ZM2.5 15h19m-19 3h16m-16 3.5h16M17 19.75a1.5 1.75 0 1 0 3 0a1.5 1.75 0 1 0-3 0ZM9.5 6h5m-5 3h5");
}

</style>
