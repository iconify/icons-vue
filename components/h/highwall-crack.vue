<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lp475fcdg"/><path class="qco5sfvdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:highwall-crack" /></template>
<style>
.lp475fcdg {
  d: path("M2.5 20.5h19V4h-8l-5 16.5");
}

.qco5sfvdy {
  d: path("M17.5 4L16 8.5l2.5 3l-1.75 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
