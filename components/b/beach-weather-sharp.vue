<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nrk64bchc"/><path class="zc4o49b-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:beach-weather-sharp" /></template>
<style>
.nrk64bchc {
  d: path("M3.25 11.25a8.75 7.5 0 0 1 17.5 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zc4o49b-c {
  d: path("M12 3.75c-1.75 2-2.5 4.75-2.5 7.5m2.5-7.5c1.75 2 2.5 4.75 2.5 7.5m-2.5 0v7.5m-9.25 2.5c3-1.75 6-2.5 9.25-2.5s6.25.75 9.25 2.5");
}

</style>
