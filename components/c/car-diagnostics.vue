<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x2wek2hyr"/><path class="butje8jbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-diagnostics" /></template>
<style>
.butje8jbo {
  d: path("M7.5 10h2L11 6.5l2 7l1.5-3.5h2Zm4.5 7.5v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x2wek2hyr {
  d: path("M4.5 5A2.5 2.5 0 0 1 7 2.5h10A2.5 2.5 0 0 1 19.5 5v8L16 17.5H8L4.5 13Z");
}

</style>
