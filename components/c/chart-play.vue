<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o2csh_b0k"/><path class="fip6-h1-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-play" /></template>
<style>
.fip6-h1-r {
  d: path("M6.5 14L10 8.5l2.213 1.844m1.245.16L19 4.5m-4 10l6.5 3.5l-6.5 3.5Z");
}

.o2csh_b0k {
  d: path("M3.5 3v17.5h8.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
