<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="we5pfbc7i"/><path class="w_9u0rbob"/><path class="mg9xohbul"/><path class="y8y0m0wuw"/><path class="lf0aqebqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:command-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lf0aqebqg {
  d: path("M8.00145 7.99999L5.00145 8.00046C3.34459 8.00072 2.00124 6.65778 2.00098 5.00093C2.00072 3.34408 3.34365 2.00072 5.0005 2.00046C6.65736 2.0002 8.00072 3.34313 8.00098 4.99999L8.00145 7.99999Z");
}

.mg9xohbul {
  d: path("M8.00145 16.001L5.00145 16.0005C3.34459 16.0002 2.00124 17.3432 2.00098 19C2.00072 20.6569 3.34365 22.0002 5.0005 22.0005C6.65736 22.0007 8.00072 20.6578 8.00098 19.001L8.00145 16.001Z");
}

.w_9u0rbob {
  d: path("M16 16.001L19 16.0005C20.6569 16.0002 22.0002 17.3432 22.0005 19C22.0007 20.6569 20.6578 22.0002 19.0009 22.0005C17.3441 22.0007 16.0007 20.6578 16.0005 19.001L16 16.001Z");
}

.we5pfbc7i {
  d: path("M8 8H16V16H8V8Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y8y0m0wuw {
  d: path("M16 7.99999L19 8.00046C20.6569 8.00072 22.0002 6.65778 22.0005 5.00093C22.0007 3.34408 20.6578 2.00072 19.0009 2.00046C17.3441 2.0002 16.0007 3.34313 16.0005 4.99999L16 7.99999Z");
}

</style>
