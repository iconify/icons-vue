<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mztsu3b3c"/><path class="tsecy1tzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:futsal-ball" /></template>
<style>
.mztsu3b3c {
  d: path("M4 10a8 8 0 1 0 16 0a8 8 0 1 0-16 0Z");
}

.tsecy1tzo {
  d: path("m12 7l2.75 2l-1 3.5h-3.5l-1-3.5Zm0 0V2m2.75 7l4.75-1.5m-5.75 5l3 4m-6.5-4l-3 4m2-7.5L4.5 7.5m2.5 14q5-2 10 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
