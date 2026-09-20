<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pty4n2r3m"/><path class="rlk52sj8y"/><path class="n5rmljb0r"/><path class="a97qfmbix"/><path class="c7vqq5bhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chess-piece-duotone-thin" /></template>
<style>
.a97qfmbix {
  d: path("M14 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.c7vqq5bhm {
  d: path("M5 18h16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n5rmljb0r {
  d: path("M7 21v-6c0 -5 3 -8 7 -9l3 -3v3c2 2 2 5 2 7v8Z");
}

.pty4n2r3m {
  fill: currentColor;
  d: path("M7 21v-6c0 -5 3 -8 7 -9l3 -3v3c2 2 2 5 2 7v8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rlk52sj8y {
  fill: currentColor;
  d: path("M14 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
