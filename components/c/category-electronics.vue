<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jens3lv0e"/><path class="sk51xbcpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-electronics" /></template>
<style>
.jens3lv0e {
  d: path("M6.5 6.5h11v11h-11Z");
}

.sk51xbcpx {
  d: path("M9.5 9.5h5v5h-5Zm-7-.75h4M2.5 12h4m-4 3.25h4m11-6.5h4m-4 3.25h4m-4 3.25h4M8.75 2.5v4m3.25-4v4m3.25-4v4m-6.5 11v4m3.25-4v4m3.25-4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
