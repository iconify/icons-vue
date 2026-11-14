<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sb45mzb_g"/><path class="dyocuybui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fuse-glass" /></template>
<style>
.dyocuybui {
  d: path("M8.5 12C10 9.75 11 14.25 12 12s2 2.25 3.5 0");
}

.sb45mzb_g {
  d: path("M6.5 8.5h11A1.5 1.5 0 0 1 19 10v4a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 14v-4a1.5 1.5 0 0 1 1.5-1.5Zm-4 3.5H5m14 0h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
