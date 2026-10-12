<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="unth-mbra"/><path class="r1k6hwuqp"/><path class="b8xx0chut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kiwi-bird" /></template>
<style>
.b8xx0chut {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.75 9.5C20 11 21 13 21.25 15.5M8 18v3.25h2m3-3.75v3.75h2");
}

.r1k6hwuqp {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.5 8.75h.01");
}

.unth-mbra {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 18c-4 0-7-2.5-7-5.5S6 7 10 7c2 0 3.5.5 4.75 0c1.75-1 4-.25 4.25 1.75c0 1.75-1.25 2.5-2 4c-.75 3-3.5 5.25-7 5.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
