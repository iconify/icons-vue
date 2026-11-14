<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yb4l-1b5j"/><path class="lq-u43b4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forecast-refresh" /></template>
<style>
.lq-u43b4a {
  d: path("M15.25 2.5L16 5l-2.5.75m-4 8.75h5a2 2 0 0 0 0-4a3 3 0 0 0-5.5.75a1.65 1.65 0 0 0 .5 3.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yb4l-1b5j {
  d: path("M12 4a8 8 0 1 1-6.928 4");
}

</style>
