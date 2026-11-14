<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4-58qhir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:end-to-end-encryption" /></template>
<style>
.e4-58qhir {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6H8v12H2.5ZM16 6h5.5v12H16Zm-6.75 5h5.5v5h-5.5Zm1 0V9.75a1.75 1.75 0 0 1 3.5 0V11");
}

</style>
