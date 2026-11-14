<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cx9aeccnc"/><path class="rtdf3sbza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:art-class" /></template>
<style>
.cx9aeccnc {
  d: path("M15 12H3V2.5h13.5v8.7M6 12l-2.5 9.5m10-9.5l.551.952M9.75 12v9.5");
}

.rtdf3sbza {
  d: path("M6.5 7.25Q8.25 5 10 7.25t3.5 0m2.5 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
