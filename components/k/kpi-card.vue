<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y6t8wrg7l"/><path class="g2m7vcbqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kpi-card" /></template>
<style>
.g2m7vcbqg {
  d: path("m6 15l3.5-2.5l3 1.5L18 9.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y6t8wrg7l {
  d: path("M2.5 4.5h19v15h-19ZM6 9h4");
}

</style>
