<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qtac65cch"/><path class="xpg2eebjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dinner" /></template>
<style>
.qtac65cch {
  d: path("M8.25 12a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM2.5 3v5a1.5 1.5 0 0 0 3 0V3M4 9.5V21m15.5 0V3c2 1.5 2 6 2 9.5h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xpg2eebjn {
  d: path("M11 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
