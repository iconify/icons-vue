<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="j2rvsqb3w"/><path class="io41kcboo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kitchen-scale-sharp" /></template>
<style>
.io41kcboo {
  d: path("M9 17a3 3 0 0 1 6 0m-3 0l1.25-1.75");
}

.j2rvsqb3w {
  d: path("M4.25 8.5h15.5M12 8.5V11m-6 0h13l.19.98l1.62 8.29l.19.98H3l.19-.98l1.62-8.29L5 11z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
