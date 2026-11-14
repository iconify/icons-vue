<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ozjoogbzb"/><path class="yhvj5gbzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kokedama" /></template>
<style>
.ozjoogbzb {
  d: path("M7 16.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm3.5-12.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm1.5 1.5v6.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yhvj5gbzq {
  d: path("M12 11.5q-4 0-6-3q4-.5 6 3Zm0 0q4 0 6-3q-4-.5-6 3Z");
}

</style>
