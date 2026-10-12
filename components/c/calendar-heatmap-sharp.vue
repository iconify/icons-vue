<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bs5r763io"/><path class="hiw3htxoe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-heatmap-sharp" /></template>
<style>
.bs5r763io {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v17.5H2.75zm5.25-1v3m8-3v3m-13.25 3h18.5");
}

.hiw3htxoe {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 11.5h.01m7.99 0h.01m3.99 0h.01M6 14.88h.01m3.99 0h.01m3.99 0h.01M10 18.25h.01m7.99 0h.01M9.5 11h1v1h-1Zm8 3.38h1v1h-1Zm-12 3.37h1v1h-1Zm8 0h1v1h-1Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
