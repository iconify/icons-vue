<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwjncbc1x"/><path class="ne9z2jngk"/><path class="q15kkdbtw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dj-cue" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ne9z2jngk {
  d: path("M5.5 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.pwjncbc1x {
  d: path("M6 4h12a3.5 3.5 0 0 1 3.5 3.5v9A3.5 3.5 0 0 1 18 20H6a3.5 3.5 0 0 1-3.5-3.5v-9A3.5 3.5 0 0 1 6 4");
}

.q15kkdbtw {
  d: path("M11.375 8.375za.895.895 0 0 1-.755 1.375h-.24a.895.895 0 0 1-.755-1.375a1.037 1.037 0 0 1 1.75 0M18.5 7.5v9");
}

</style>
