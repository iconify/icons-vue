<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u1klnyb3u"/><path class="rwt37ub5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gold-price-outline-bold" /></template>
<style>
.rwt37ub5x {
  d: path("m5 9.5 4 -4 3 3L18.5 2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u1klnyb3u {
  d: path("m2 18.5 5 -5h10l5 5Z");
}

</style>
