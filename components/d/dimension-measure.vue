<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc3j7_2rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dimension-measure" /></template>
<style>
.vc3j7_2rv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h13V15h-13Zm2 15l-2 1.5l2 1.5m-2-1.5h13m-2-1.5l2 1.5l-2 1.5m4.5-16l1.5-2l1.5 2m-1.5-2V15M18 13l1.5 2l1.5-2");
}

</style>
