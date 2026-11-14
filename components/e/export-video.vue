<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p5yiuvbdz"/><path class="tcd6eibuv"/><path class="ad6-v8gsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:export-video" /></template>
<style>
.ad6-v8gsc {
  d: path("M12 18.75v-4.5M9.75 16.5L12 14.25l2.25 2.25");
}

.p5yiuvbdz {
  d: path("M5 2.5h14v9H5Z");
}

.tcd6eibuv {
  d: path("M10.5 5.25L14 7l-3.5 1.75ZM3 16v5.5h18V16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
