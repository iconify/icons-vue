<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t24b29hoh"/><path class="vxo3gieyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gear-shape" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t24b29hoh {
  d: path("m9.654 4.934l.295-1.079a1.5 1.5 0 0 1 1.447-1.105h1.208a1.5 1.5 0 0 1 1.447 1.105l.295 1.079a1.5 1.5 0 0 0 .652.877l.945.591a1.5 1.5 0 0 0 1.19.175l1.05-.286a1.5 1.5 0 0 1 1.661.642l.51.802a1.5 1.5 0 0 1-.205 1.866l-.71.71a1.5 1.5 0 0 0-.439 1.06v1.258a1.5 1.5 0 0 0 .439 1.06l.71.71a1.5 1.5 0 0 1 .205 1.866l-.51.802a1.5 1.5 0 0 1-1.661.642l-1.05-.286a1.5 1.5 0 0 0-1.19.175l-.945.591a1.5 1.5 0 0 0-.652.877l-.295 1.079a1.5 1.5 0 0 1-1.447 1.105h-1.208a1.5 1.5 0 0 1-1.447-1.105l-.295-1.079a1.5 1.5 0 0 0-.652-.877l-.945-.591a1.5 1.5 0 0 0-1.19-.175l-1.05.286a1.5 1.5 0 0 1-1.661-.642l-.51-.802a1.5 1.5 0 0 1 .205-1.866l.71-.71A1.5 1.5 0 0 0 5 12.629v-1.258a1.5 1.5 0 0 0-.439-1.06l-.71-.71a1.5 1.5 0 0 1-.205-1.866l.51-.802a1.5 1.5 0 0 1 1.661-.642l1.05.286a1.5 1.5 0 0 0 1.19-.175l.945-.591a1.5 1.5 0 0 0 .652-.877");
}

.vxo3gieyf {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
