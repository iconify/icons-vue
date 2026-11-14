<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lv2eh0ojq"/><path class="c0pnds3kx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brew-airlock" /></template>
<style>
.c0pnds3kx {
  d: path("M12 7V5.5a2 2 0 0 1 4 0a2 2 0 0 0 4 0v-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lv2eh0ojq {
  d: path("M6.5 21.5h11a2 2 0 0 0 2-2v-4c0-3-5.5-3-5.5-5v-1h-4v1c0 2-5.5 2-5.5 5v4a2 2 0 0 0 2 2m4-14.5h3a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 13.5 9.5h-3a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 10.5 7");
}

</style>
