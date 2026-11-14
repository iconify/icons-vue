<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="g0b8ox_pu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:checker" /></template>
<style>
.g0b8ox_pu {
  fill: currentColor;
  d: path("M7.25 2.5H12v4.75H7.25Zm9.5 0H19A2.5 2.5 0 0 1 21.5 5v2.25h-4.75ZM2.5 7.25h4.75V12H2.5Zm9.5 0h4.75V12H12ZM7.25 12H12v4.75H7.25Zm9.5 0h4.75v4.75h-4.75ZM2.5 16.75h4.75v4.75H5A2.5 2.5 0 0 1 2.5 19Zm9.5 0h4.75v4.75H12Z");
}

.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
