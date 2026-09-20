<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="y09n-7bbz"/><path class="xjxf-fbjv"/><path class="z0_yphh3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:forecast-outline-bold" /></template>
<style>
.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xjxf-fbjv {
  d: path("m13 9 2 -2");
}

.y09n-7bbz {
  d: path("m6 16 5 -5");
}

.z0_yphh3l {
  d: path("m17 5 2 -2");
}

</style>
