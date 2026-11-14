<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g26tobccd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dehaze" /></template>
<style>
.g26tobccd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13L9 3.5l4.25 6l2.5-3L21.5 13M3 16.75q2.25-1.25 4.5 0t4.5 0t4.5 0t4.5 0M3 20.5q2.25-1.25 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
