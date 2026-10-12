<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r_i2e5b1n"/><path class="ew4xwsbas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hoodie-sharp" /></template>
<style>
.ew4xwsbas {
  d: path("m9 5l3 4l3-4m-4.5 3.5V12m3-3.5V12M6 13v3.75M18 13v3.75m-9.5 4.5V18l1.5-2h4l1.5 2v3.25");
}

.r_i2e5b1n {
  d: path("M10 5h5l.92.39l1.66.72l.92.39l.27.96l2.21 8.08l.27.96l-.97.22l-1.31.31l-.97.22v4H6v-4l-.97-.22l-1.31-.31l-.97-.22l.27-.96l2.21-8.08l.27-.96l.92-.39l1.66-.72L9 5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
