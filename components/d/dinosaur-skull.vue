<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mfr22jb8h"/><path class="vzbnq0ams"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dinosaur-skull" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mfr22jb8h {
  d: path("M3 12c0-4.75 3-7.5 7-7.5l7.5 2c2.5.75 3.5 2 3.5 4V12h-3l-1.25 2.75L15.5 12H12l-1.25 2.75L9.5 12Zm2 2.75q.5 5.75 5 5.75h9.5");
}

.vzbnq0ams {
  d: path("M7 8.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
