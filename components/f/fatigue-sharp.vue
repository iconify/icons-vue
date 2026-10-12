<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="m2rbgvbce"/><path class="tq4h01ogt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fatigue-sharp" /></template>
<style>
.m2rbgvbce {
  cx: 7.75px;
  cy: 7.25px;
  r: 3.25px;
}

.tq4h01ogt {
  d: path("M2.75 20.75V18.5a5 5 0 0 1 10 0v2.25ZM15.5 9.25h5.75v12H15.5zM17.25 7h2.25m-1.125 9.75v1.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
