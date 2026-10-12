<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="d3f4el0zq"/><path class="gixryebmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:feather-mask-sharp" /></template>
<style>
.d3f4el0zq {
  d: path("M11.36 10.23A5.5 5.5 0 0 1 6.7 4.68a5.5 5.5 0 0 1 4.66 5.55ZM12 10a5.5 5.5 0 0 1 0-7.25A5.5 5.5 0 0 1 12 10Zm.64.23a5.5 5.5 0 0 1 4.66-5.55a5.5 5.5 0 0 1-4.66 5.55Zm-9.89 2.02c3-1 6.25-.75 9.25 1c3-1.75 6.25-2 9.25-1c0 4.5-2.25 7.25-5.25 7.25c-1.75 0-3-1-4-2.5c-1 1.5-2.25 2.5-4 2.5c-3 0-5.25-2.75-5.25-7.25Z");
}

.gixryebmx {
  d: path("M5.5 15.25c1.25-1.25 3-1.25 4.25 0c-1.25 1.25-3 1.25-4.25 0Zm8.75 0c1.25-1.25 3-1.25 4.25 0c-1.25 1.25-3 1.25-4.25 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
