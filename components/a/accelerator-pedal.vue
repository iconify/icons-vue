<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l1r5d1bwi"/><path class="as5n0ffis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:accelerator-pedal" /></template>
<style>
.as5n0ffis {
  d: path("m9 21.5l3-4l3 4m-11 0h16M11.434 7.754l4.431.781m-5.213 3.65l4.432.782");
}

.l1r5d1bwi {
  d: path("m9.507 2.844l9.848 1.737l-2.431 13.787l-9.848-1.736Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
