<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="x_v1iebfy"/><path class="inmyl9hqx"/><circle class="qfz3y5phf"/><path class="z41zubbty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:competitor-sharp" /></template>
<style>
.inmyl9hqx {
  d: path("M3.5 21.25h5.75v-.75c0-2.6-1.5-4.5-3.25-4.5s-3.25 1.9-3.25 4.5v.75z");
}

.qfz3y5phf {
  cx: 18px;
  cy: 10.25px;
  r: 2.25px;
}

.x_v1iebfy {
  cx: 6px;
  cy: 10.25px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z41zubbty {
  d: path("M15.5 21.25h5.75v-.75c0-2.6-1.5-4.5-3.25-4.5s-3.25 1.9-3.25 4.5v.75zm-2.25-17.5l-2.5 5h2.5l-2.5 5");
}

</style>
