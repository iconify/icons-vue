<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dk3zl2b7m"/><path class="qvu8j6byn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alarm-ring" /></template>
<style>
.dk3zl2b7m {
  d: path("M5.5 13a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

.qvu8j6byn {
  d: path("M12 10v3l2 1.5m-9.5-8l3-3m12 3l-3-3M3.39 17.015a9.5 9.5 0 0 1 0-8.03m17.22 0a9.5 9.5 0 0 1 0 8.03M7.75 18.25l-1.5 2.25m10-2.25l1.5 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
