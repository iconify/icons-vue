<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jw3gt3abu"/><path class="p6tt7ox7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:elevation-gain" /></template>
<style>
.jw3gt3abu {
  d: path("M2.5 20.5L10 4l7.5 16.5Z");
}

.p6tt7ox7e {
  d: path("m6.75 11l1.75 1.75l1.5-1.5l1.75 1.5l1.5-1.75m6 6.5V4M17 6.25L19.25 4l2.25 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
