<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r503y7brq"/><path class="zu20fmbbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accelerator-pedal-sharp" /></template>
<style>
.r503y7brq {
  d: path("M8 2.75h8V18.5H8zm-2.5 18.5h13M12 18.5v2.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zu20fmbbg {
  d: path("M10.25 12.5L12 7.75l1.75 4.75m-3-1.5h2.5m-3 4.25h3.5");
}

</style>
