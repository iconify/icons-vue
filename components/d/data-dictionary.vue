<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h4y72tbat"/><path class="uorimvbav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-dictionary" /></template>
<style>
.h4y72tbat {
  d: path("M19 17V2.5H7.5A2.5 2.5 0 0 0 5 5v14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uorimvbav {
  d: path("M19 17H7.5a2.25 2.25 0 0 0 0 4.5H19M9 8h6m-6 4h4");
}

</style>
