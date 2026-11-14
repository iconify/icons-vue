<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nk30f8byu"/><path class="xl5hocbhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:backdrop-flower-wall" /></template>
<style>
.nk30f8byu {
  d: path("M2.5 2.5h19v14h-19Zm3.5 14v5m12-5v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xl5hocbhe {
  d: path("M10.5 8a2 2 0 1 1 3 0a2 2 0 1 1 0 3a2 2 0 1 1-3 0a2 2 0 1 1 0-3ZM12 9.5h.01");
}

</style>
