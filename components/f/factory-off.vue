<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsi5byf-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:factory-off" /></template>
<style>
.tsi5byf-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.562 20.5H3v-9l2.83-1.698m6.86-1.116L13 8.5v.538m2.438 2.462H16.5v-8h4v13.038M6.5 15.5h2m-5-12l17 17");
}

</style>
