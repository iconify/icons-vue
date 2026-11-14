<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vi-pg127j"/><path class="k27f4r3fh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aviator-goggles" /></template>
<style>
.k27f4r3fh {
  d: path("M3.25 10.5C2 20 22 20 20.75 10.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vi-pg127j {
  d: path("M3.25 10.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm10 0a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm-2.5 0q1.25-1.5 2.5 0");
}

</style>
