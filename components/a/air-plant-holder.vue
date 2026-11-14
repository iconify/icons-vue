<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pedet9biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-plant-holder" /></template>
<style>
.pedet9biq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 21.5h10m-5-7v7M8.5 12q3.5 5 7 0m-3.5-.25Q9 8 5.5 6m6.5 5.75V2.5m0 9.25Q15 8 18.5 6");
}

</style>
