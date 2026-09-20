<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="co4ft5twa"/><path class="f8gsx7b5s"/><path class="h552nsb3x"/><path class="c0kdmnbne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:kayak-outline-bold" /></template>
<style>
.c0kdmnbne {
  d: path("M21 5h-3v6h3Z");
}

.co4ft5twa {
  d: path("M3 15c4 -2 14 -2 18 0 -4 5 -14 5 -18 0");
}

.f8gsx7b5s {
  d: path("M6 8h12");
}

.h552nsb3x {
  d: path("M3 5h3v6H3Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
