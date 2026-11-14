<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bfvowz03s"/><path class="nb0nz450i"/><path class="z2org3m-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:house-flipping" /></template>
<style>
.bfvowz03s {
  d: path("m5 13.5l7-6l7 6v8H5Z");
}

.nb0nz450i {
  d: path("M10 21.5V18h4v3.5M4 11a8 7.5 0 0 1 16 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z2org3m-a {
  d: path("M18.25 9.25L20 11l1.75-1.75");
}

</style>
