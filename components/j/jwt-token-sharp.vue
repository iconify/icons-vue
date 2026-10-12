<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="uirovflrg"/><path class="nihmz0bdx"/><path class="e8bv_pb1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jwt-token-sharp" /></template>
<style>
.e8bv_pb1o {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.5h.01M8 17h.01");
}

.nihmz0bdx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-3 5h1.75m6.5 0H17M11.25 17H17");
}

.uirovflrg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3.5h16v17H4z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
