<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ifawrxf5w"/><path class="r2tm17bxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basketball-pass-chest" /></template>
<style>
.ifawrxf5w {
  d: path("M8.75 5.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM3 21.5v-4c0-3 1-4.5 2.5-5m15.5 9v-4c0-3-1-4.5-2.5-5m-11.25 4a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0Z");
}

.r2tm17bxy {
  d: path("M8.75 13.25q3.25 3.25 0 6.5m6.5-6.5q-3.25 3.25 0 6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
