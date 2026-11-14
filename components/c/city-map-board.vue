<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kkdql4bcp"/><path class="kxd3e3lia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:city-map-board" /></template>
<style>
.kkdql4bcp {
  d: path("M2.5 2.5h19v14h-19Zm9.5 14v5");
}

.kxd3e3lia {
  d: path("M2.5 8.5c3 0 4.5 3.5 6 8m7.5-4s-2.25-2.25-2.25-4a2.25 2.25 0 0 1 4.5 0c0 1.75-2.25 4-2.25 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
