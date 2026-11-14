<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oqk4khbli"/><path class="hu20cgsdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lawn-sprinkler-zone" /></template>
<style>
.hu20cgsdk {
  d: path("M4.75 6a9.5 9.5 0 0 1 14.5 0M2.5 18.5a9.5 3 0 1 0 19 0a9.5 3 0 1 0-19 0Z");
}

.oqk4khbli {
  d: path("M10 10.5h4v3h-4Zm2 3v7M6.75 9a6 6 0 0 1 10.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
