<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lledrh64j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:convex-lens" /></template>
<style>
.lledrh64j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3c3 4 3 14 0 18c-3-4-3-14 0-18ZM2.5 7.5h6m-6 9h6m7-9l6 4.5l-6 4.5");
}

</style>
