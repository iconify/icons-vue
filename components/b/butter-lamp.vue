<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ntmiu2azk"/><path class="lfrch9b_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:butter-lamp" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lfrch9b_e {
  d: path("m9.75 19.75l.36-.841A1.5 1.5 0 0 1 11.489 18h1.022a1.5 1.5 0 0 1 1.379.909l.36.841a1.255 1.255 0 0 1-1.154 1.75h-2.192a1.255 1.255 0 0 1-1.154-1.75M12 2.5q4.5 4.875 0 6.75q-4.5-1.875 0-6.75");
}

.ntmiu2azk {
  d: path("M4 12h16c0 4-3.5 6-8 6s-8-2-8-6");
}

</style>
