<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="upviaib9j"/><path class="eh_jugbkc"/><path class="v2r-s_jco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ground-floor" /></template>
<style>
.eh_jugbkc {
  fill: currentColor;
  d: path("M6 15h12v4H6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.upviaib9j {
  d: path("M6 15V8.5L12 3l6 5.5V15");
}

.v2r-s_jco {
  d: path("M2.5 21.5h19M6 10h12");
}

</style>
