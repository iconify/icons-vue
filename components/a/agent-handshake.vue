<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lsds1qe0q"/><path class="yoexb_jgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:agent-handshake" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lsds1qe0q {
  d: path("M2.5 7.5h3v7h-3m19-7h-3v7h3M5.5 9l4-2.5H14l4.5 2v5l-5 4c-.75.5-1.75.5-2.5 0l-5.5-4Z");
}

.yoexb_jgm {
  d: path("m14 6.5l-3.5 4a1.25 1.25 0 0 0 1.75 1.75L15 10");
}

</style>
