<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpun8bbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cornet" /></template>
<style>
.mpun8bbbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10.5h10.5l7-3.5v10l-7-3.5h-6a2.75 2.75 0 0 0 0 5.5H12m-6-8.5v-5m3 5v-5m3 5v-5");
}

</style>
