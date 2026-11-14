<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xd5jkgbsq"/><path class="oorugs-hg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-walker" /></template>
<style>
.oorugs-hg {
  d: path("M14 11c-1-4-3-6-6-6.5m-4 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xd5jkgbsq {
  d: path("M4.5 13c0-1.25.75-2 2-2H14l1.5-3.5L17 9h2l1.75 2L19 12.5h-1.5V14c0 1.25-.75 2-2 2h-9c-1.25 0-2-.75-2-2ZM7 16v4.5m8.5-4.5v4.5M4.5 12l-2-2.5");
}

</style>
