<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w232_mb1n"/><path class="yptcbs8tl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ar-label" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w232_mb1n {
  d: path("M4.5 2.5h15v7h-15Zm7.5 7V13m0 0l4 2v4.5l-4 2l-4-2V15Z");
}

.yptcbs8tl {
  d: path("m8 15l4 2l4-2m-4 2v4.5");
}

</style>
