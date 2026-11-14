<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tx5je51ed"/><path class="yl9hdvbpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:joint" /></template>
<style>
.tx5je51ed {
  d: path("M10.25 2.5v5.25m3.5-5.25v5.25M9 10.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yl9hdvbpc {
  d: path("M17.479 10.729a5.5 5.5 0 0 1-10.958 0M10 15.5v6m4-6v6");
}

</style>
