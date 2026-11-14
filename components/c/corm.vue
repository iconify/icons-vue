<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="enlaaibkm"/><path class="h9px6z5oc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:corm" /></template>
<style>
.enlaaibkm {
  d: path("M12 6.5c4.5 0 8 3 8 7c0 3-2.5 4.5-8 4.5s-8-1.5-8-4.5c0-4 3.5-7 8-7Z");
}

.h9px6z5oc {
  d: path("M10.5 6.75q.5-3.25 2-4.25q1 2 1 4.25M7 11.5q5 2 10 0M9.5 18L9 20.5m3-2.5v3m2.5-3l.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
