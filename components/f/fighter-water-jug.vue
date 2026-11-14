<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u0sejybgi"/><path class="p5orp9ctt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fighter-water-jug" /></template>
<style>
.p5orp9ctt {
  d: path("M6.5 15q2.75-1.75 5.5 0t5.5 0");
}

.u0sejybgi {
  d: path("M2.5 8.5h19V21h-19Zm2-4h6v4h-6Zm8.5 4v-4a1 1 0 0 1 1-1h4.5a1 1 0 0 1 1 1v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
