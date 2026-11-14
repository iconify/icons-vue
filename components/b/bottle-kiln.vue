<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zhqjambpz"/><path class="j21s3r_de"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bottle-kiln" /></template>
<style>
.j21s3r_de {
  d: path("M10 21.5v-3a2 2 0 0 1 4 0v3M12 6.25c-1.5-1 1.5-2.75 0-3.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zhqjambpz {
  d: path("M4.5 21.5C4 16 7 13 10 10.5V9h4v1.5c3 2.5 6 5.5 5.5 11Z");
}

</style>
