<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z32-znt-c"/><path class="l9hu2h1fj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drain-cleaner" /></template>
<style>
.l9hu2h1fj {
  d: path("M9 12h6v5H9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z32-znt-c {
  d: path("M9.5 2.5h5V6L18 9v10.5a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2V9l3.5-3Z");
}

</style>
