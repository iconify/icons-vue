<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nm0b5y_ev"/><path class="xboiotb1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gps-tracker-sharp" /></template>
<style>
.nm0b5y_ev {
  d: path("M4.75 6.75h14.5v14.5H4.75zm11.25 0v-4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xboiotb1p {
  d: path("M12 18.5s-3.5-3-3.5-5.75a3.5 3.5 0 0 1 7 0c0 2.75-3.5 5.75-3.5 5.75Z");
}

</style>
