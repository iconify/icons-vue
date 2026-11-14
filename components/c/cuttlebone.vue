<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wiyn8ibkm"/><path class="xwusonbim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cuttlebone" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wiyn8ibkm {
  d: path("M3 12c0-4 4-5.5 9-5.5c4 0 7 2.5 9.5 5.5c-2.5 3-5.5 5.5-9.5 5.5c-5 0-9-1.5-9-5.5Z");
}

.xwusonbim {
  d: path("M8 10q1 2 0 4m4-4.5q1 2.5 0 5m4-4q.75 1.5 0 3");
}

</style>
