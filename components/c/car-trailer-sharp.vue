<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="eng6q4bqp"/><circle class="n68tfnh1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-trailer-sharp" /></template>
<style>
.eng6q4bqp {
  d: path("M2.75 8.75h13v9h-13zm0 3h13m0 2.5h5.5m-2 0v4m-1 0h2");
}

.n68tfnh1s {
  cx: 9.25px;
  cy: 17.75px;
  r: 2.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
