<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="epitsishz"/><path class="x1w6-dbwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kid-girl" /></template>
<style>
.epitsishz {
  d: path("M7.5 9.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM5 21.5c0-3 3-4.5 7-4.5s7 1.5 7 4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1w6-dbwb {
  d: path("M4.5 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
