<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7r462-sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drone-scan" /></template>
<style>
.y7r462-sb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5.5h5V9h-5Zm0 1.75H5V3.5m9.5 3.75H19V3.5m-16.5 0h5m9 0h5M9.5 12L5 20.5m9.5-8.5l4.5 8.5m-11.5-4h9");
}

</style>
