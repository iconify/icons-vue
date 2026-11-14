<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eanni_blz"/><path class="b5zvu7t3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-search" /></template>
<style>
.b5zvu7t3h {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5m-4.25 12.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm4.5 2l2.25 2.25");
}

.eanni_blz {
  d: path("M3.5 3v17.5h9.6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
