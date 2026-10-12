<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o0en1ac3r"/><path class="aaqqw80hv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dodecahedron-sharp" /></template>
<style>
.aaqqw80hv {
  d: path("m12.81 8.09l2.9 2.1l.81.59l-.31.95l-1.11 3.41l-.31.95H9.21l-.31-.95l-1.11-3.41l-.31-.95l.81-.59l2.9-2.1l.81-.59zM12 6.5V3.4m5.47 7.07l2.71-1.13m-4.8 7.56l1.67 2.06M8.62 16.9l-1.67 2.06m-.42-8.49L3.82 9.34");
}

.o0en1ac3r {
  d: path("m13.19 2.99l3.15 1.02l1.19.39l.73 1.01l1.95 2.67l.73 1.02v5.8l-.73 1.02l-1.95 2.67l-.73 1.01l-1.19.39l-3.15 1.02l-1.19.39l-1.19-.39l-3.15-1.02l-1.19-.39l-.73-1.01l-1.95-2.67l-.73-1.02V9.1l.73-1.02l1.95-2.67l.73-1.01l1.19-.39l3.15-1.02L12 2.6z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
