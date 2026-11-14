<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n1v7kl2gq"/><path class="lzwq3kbvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:builders-bucket" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lzwq3kbvr {
  d: path("M7.5 13q2.25-1.5 4.5 0t4.5 0");
}

.n1v7kl2gq {
  d: path("M5 9h14l-1.5 11a1.5 1.5 0 0 1-1.5 1.5H8A1.5 1.5 0 0 1 6.5 20Zm0 0c0-6 14-6 14 0");
}

</style>
