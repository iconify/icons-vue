<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="os95oubfs"/><path class="opwpyis2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hazard-lights-sharp" /></template>
<style>
.opwpyis2y {
  d: path("m12.49 10.12l3.27 5.76l.49.87h-8.5l.49-.87l3.27-5.76l.49-.87z");
}

.os95oubfs {
  d: path("M12.97 4.75L20.28 18l.97 1.75H2.75L3.72 18l7.31-13.25L12 3z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
