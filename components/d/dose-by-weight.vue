<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y81fy4p5t"/><path class="cwo6e2z_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dose-by-weight" /></template>
<style>
.cwo6e2z_u {
  d: path("M9.25 16.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm2.75 0l1.75-1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y81fy4p5t {
  d: path("M3 8.5h18m-11 0v-3l1-1v-2h2v2l1 1v3m-9.5 2.75h15V21.5h-15Z");
}

</style>
