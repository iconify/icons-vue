<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2wbs8bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gas-state" /></template>
<style>
.f2wbs8bvc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6h17v15.5h-17ZM8 2.5h8V6H8ZM7.5 10h.01M13 9.5h.01M10 14h.01m6.49-1h.01M7.5 18h.01M14 18h.01");
}

</style>
