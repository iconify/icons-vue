<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r88vt3rdo"/><path class="fdecw5qae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-quality-sensor" /></template>
<style>
.fdecw5qae {
  d: path("M9.75 16.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM8 8.25Q6.5 6.75 8 5.5t0-2.75m4 5.5q-1.5-1.5 0-2.75t0-2.75m4 5.5q-1.5-1.5 0-2.75t0-2.75");
}

.r88vt3rdo {
  d: path("M5 11h14v10.5H5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
