<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dwh_bfb1n"/><path class="agviwebls"/><path class="vz9lloblv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:imam-cap-sharp" /></template>
<style>
.agviwebls {
  d: path("M3.75 13c0-1.75 3.75-2.75 8.25-2.75s8.25 1 8.25 2.75v5c0 1.75-3.75 3.25-8.25 3.25S3.75 19.75 3.75 18Z");
}

.dwh_bfb1n {
  d: path("M7.25 10.75c.25-4.5 2.25-8 4.75-8s4.5 3.5 4.75 8c-1.5-.35-3-.5-4.75-.5s-3.25.15-4.75.5Z");
}

.vz9lloblv {
  d: path("M3.75 15.5c4.75 1.75 11.75 1.75 16.5 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
