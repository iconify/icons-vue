<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wbop_o7qc"/><path class="tvkkhvbna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hot-water-tank-large" /></template>
<style>
.tvkkhvbna {
  d: path("M12 10.5c.5 2 3 2.5 3 5.25a3 3 0 0 1-6 0c0-1.5 1-2.5 1.5-3c.25 1 .75 1.5 1.25 1.5c0-1-.25-2.75.25-3.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wbop_o7qc {
  d: path("M6 7.5a6 5 0 0 1 12 0v12a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2ZM2.5 12H6m12 4.5h3.5");
}

</style>
