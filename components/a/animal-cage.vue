<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq1bbzbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:animal-cage" /></template>
<style>
.oq1bbzbji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21v-9a7.5 7.5 0 0 1 15 0v9m-17-2.5h19M8 5.75V18.5m4-16v16m4-12.75V18.5");
}

</style>
