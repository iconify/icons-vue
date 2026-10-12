<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpjh4ab5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-shaka-sharp" /></template>
<style>
.wpjh4ab5p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.01 4.97L9.7 8.41l.46.59H16v6.14l.56.5l2.09 1.85l.93.83l-.83.93l-.83.93l-.93-.83l-2.09-1.85l-.56-.5H8v-6.7l-.46-.59L5.03 6.5l-.77-.98l.99-.77l.99-.77zM10.25 13h4.5M9.25 3l1.439.32l.811 1.18M2.75 8.75l.32 1.439L4.25 11");
}

</style>
