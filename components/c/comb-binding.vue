<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d4_a89bmh"/><path class="aof00x69w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:comb-binding" /></template>
<style>
.aof00x69w {
  d: path("M6 2.5h2.5v5H6Zm4.75 0h2.5v5h-2.5Zm4.75 0H18v5h-2.5Z");
}

.d4_a89bmh {
  d: path("M4.5 4.5h15V19h-15Zm2 17h11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
