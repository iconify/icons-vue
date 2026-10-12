<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fzi8w9bnl"/><path class="jrbsd48nl"/><path class="uld2jcc5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:banana" /></template>
<style>
.fzi8w9bnl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.25 7.25h3C21.5 15 16.5 21.25 7.5 19.5c-1.1-.2-1.6-1-1.6-1.9s.5-1.7 1.1-1.85c3.25-2.25 6.5-5 10.25-8.5");
}

.jrbsd48nl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.91 15.93c1.61-.99 2.95-2.37 3.96-4.01m.38-4.67v-3h3v3");
}

.uld2jcc5q {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.25 17.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
