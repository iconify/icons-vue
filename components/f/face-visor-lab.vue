<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wpcn3sith"/><path class="xj6p9ubqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-visor-lab" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wpcn3sith {
  d: path("M7 7.5c0-3.25 2.25-5 5-5s5 1.75 5 5");
}

.xj6p9ubqe {
  d: path("M7 7.5q5-1.25 10 0a2 2 0 0 1 0 4q-5-1.25-10 0a2 2 0 0 1 0-4Zm0 4c0 3.25 2.25 5.25 5 5.25s5-2 5-5.25m-13 10q8-3.5 16 0");
}

</style>
