<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y3q4v0k2f"/><path class="nkrv57bmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-embed" /></template>
<style>
.nkrv57bmi {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5M16.5 15l-2 3l2 3m3-6l2 3l-2 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y3q4v0k2f {
  d: path("M3.5 3v17.5h9.3");
}

</style>
