<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wei_cjtfb"/><path class="nh0r1xb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:barn-open" /></template>
<style>
.nh0r1xb3w {
  d: path("M9.5 21v-8h5v8m-5-8L6 14.5V21m8.5-8l3.5 1.5V21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wei_cjtfb {
  d: path("M3 21V10.5L6 6l6-3l6 3l3 4.5V21Z");
}

</style>
