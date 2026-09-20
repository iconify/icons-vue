<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="x9ne0caxf"/><path class="ks612kq_w"/><path class="boj5jfb_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:budget-forecast-outline-bold" /></template>
<style>
.boj5jfb_k {
  d: path("M13.5 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ks612kq_w {
  d: path("m7 17 5 -5");
}

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

.x9ne0caxf {
  d: path("M7 8h12");
}

</style>
