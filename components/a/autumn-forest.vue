<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="so9--hnql"/><path class="ckhh_097k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:autumn-forest" /></template>
<style>
.ckhh_097k {
  d: path("M14.25 6.25A4.5 4.5 0 1 1 13.5 13m3.5 1.5v7m-14.5-1C2.5 18 4 16.75 6 16.75C6 19 4.5 20.5 2.5 20.5Z");
}

.so9--hnql {
  d: path("M3 9a6 6 0 1 0 12 0A6 6 0 1 0 3 9Zm6 6v6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
