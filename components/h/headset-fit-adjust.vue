<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ghy19tbmf"/><path class="e5q362t5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:headset-fit-adjust" /></template>
<style>
.e5q362t5j {
  d: path("M8.25 4.25L10 6L8.25 7.75m7.5-3.5L14 6l1.75 1.75");
}

.ghy19tbmf {
  d: path("M4.5 11h15a2 2 0 0 1 2 2v4.5a2 2 0 0 1-2 2H15l-1.5-2h-3l-1.5 2H4.5a2 2 0 0 1-2-2V13a2 2 0 0 1 2-2Zm.5 0c0-3.5 2.5-5 5-5m4 0c2.5 0 5 1.5 5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
