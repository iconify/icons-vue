<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u2m3lpb8w"/><path class="rkojmkb-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:election-coverage" /></template>
<style>
.rkojmkb-x {
  d: path("M8.5 10.5L11 13l4.5-4.5");
}

.u2m3lpb8w {
  d: path("M2.5 3.5h19v14h-19Zm6 17.5h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
