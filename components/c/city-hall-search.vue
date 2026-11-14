<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yb6gqr1-x"/><path class="xql0hkbim"/><path class="q3mnfrbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:city-hall-search" /></template>
<style>
.q3mnfrbtv {
  d: path("M10.75 13.5V9L12 8l1.25 1v4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xql0hkbim {
  d: path("M7.25 11a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0Zm8.25 3.5l4 4");
}

.yb6gqr1-x {
  d: path("m2.5 4.5l6-1.5l7 1.5l6-1.5v14.5l-6 1.5l-7-1.5l-6 1.5Z");
}

</style>
