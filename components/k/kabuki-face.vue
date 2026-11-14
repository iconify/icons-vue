<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zze1rkzoh"/><path class="wnws9nbfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kabuki-face" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wnws9nbfe {
  d: path("M10.5 10.5q-2.5 0-5.25-3.25m8.25 3.25q2.5 0 5.25-3.25m-9 8.25Q7.5 15 4.5 12.75m9.75 2.75q2.25-.5 5.25-2.75");
}

.zze1rkzoh {
  d: path("M4.25 12a7.75 9.75 0 1 0 15.5 0a7.75 9.75 0 1 0-15.5 0Z");
}

</style>
