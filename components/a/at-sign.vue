<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="udfa5dztv"/><path class="wqmtfwbjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:at-sign" /></template>
<style>
.udfa5dztv {
  d: path("M8.25 12a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wqmtfwbjw {
  d: path("M15.75 8.25v5.25a2.375 2.375 0 0 0 4.75 0V12a8.5 8.5 0 1 0-3.5 6.75");
}

</style>
