<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m0xv12byo"/><path class="idcoxuhid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lash-extensions" /></template>
<style>
.idcoxuhid {
  d: path("M9.75 14a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.m0xv12byo {
  d: path("M3 14q9-10 18 0q-9 10-18 0Zm4.5-3.75L5.25 6.5M12 9V4.5m4.5 5.75l2.25-3.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
