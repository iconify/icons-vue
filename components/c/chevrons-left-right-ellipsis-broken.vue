<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ghv12qbis"/><path class="d6or4zd7k"/><path class="fthphob1f"/><path class="s8jymw4de"/><path class="ljibb1c5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevrons-left-right-ellipsis-broken" /></template>
<style>
.d6or4zd7k {
  d: path("M20.5 10.5L22 12L16 18");
}

.fthphob1f {
  d: path("M17.5 7.5L16 6");
}

.ghv12qbis {
  d: path("M8 12H8.009M11.991 12H12M15.991 12H16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ljibb1c5d {
  d: path("M6.5 7.5L8 6");
}

.s8jymw4de {
  d: path("M3.5 10.5L2 12L8 18");
}

</style>
