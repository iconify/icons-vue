<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wtwi9kb-u"/><path class="sg-bdpv7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ankle" /></template>
<style>
.sg-bdpv7n {
  d: path("M9.5 16a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wtwi9kb-u {
  d: path("M8.5 2.5V13c0 2.5-1 4-1 5.5c0 1.75 1.25 3 3 3h9c1.25 0 2-.75 1.75-1.75S19.5 18 17.5 17.5l-2.25-1.25C14.5 15.5 14 14.5 14 13V2.5");
}

</style>
