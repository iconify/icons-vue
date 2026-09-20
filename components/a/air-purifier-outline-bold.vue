<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j8arz0w3t"/><path class="f8gsx7b5s"/><path class="l0v-b4kbr"/><path class="hclo6jb2r"/><path class="ltl8_ccdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:air-purifier-outline-bold" /></template>
<style>
.f8gsx7b5s {
  d: path("M6 8h12");
}

.hclo6jb2r {
  d: path("M8 16h8");
}

.j8arz0w3t {
  d: path("M6 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.ltl8_ccdr {
  d: path("M3 6h3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
