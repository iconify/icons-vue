<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bexm-ogbi"/><path class="zysuwdm4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crescent-star-moon" /></template>
<style>
.bexm-ogbi {
  d: path("M13.75 3.5a8.75 8.75 0 1 0 6 12.25a7 7 0 1 1-6-12.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zysuwdm4l {
  d: path("m17.5 6.5l.75 2h2l-1.5 1.5l.5 2l-1.75-1.25L15.75 12l.5-2l-1.5-1.5h2Z");
}

</style>
