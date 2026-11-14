<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a2b3k3s5l"/><path class="gbz1i8b-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:house-moon" /></template>
<style>
.a2b3k3s5l {
  d: path("M11.644 20.5H3.5v-10L12 3.25l8.5 7.25v1.156m0 2.7v2.6");
}

.gbz1i8b-z {
  d: path("M20.75 19.75a3.5 3.5 0 1 1-3.5-5a3.5 3.5 0 0 0 3.5 5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
