<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jw8hkhb3d"/><path class="e5tn9ybnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coal-bucket" /></template>
<style>
.e5tn9ybnp {
  d: path("m8 9.5l2-2l2 1.25l2.5-1.5L16 9.5");
}

.jw8hkhb3d {
  d: path("M5 9.5h14l-1.5 11h-11Zm0 0C5 2 19 2 19 9.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
