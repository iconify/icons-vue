<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nwwvkoo2y"/><path class="hh9110min"/><path class="rq3kv2xzk"/><path class="hyztp1b_a"/><path class="nbsh9vihc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cache-miss-duotone-bold" /></template>
<style>
.hh9110min {
  d: path("M4 11a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

.hyztp1b_a {
  d: path("m13.5 8.5 -5 5");
}

.nbsh9vihc {
  d: path("m16 16 3.5 3.5");
}

.nwwvkoo2y {
  fill: currentColor;
  d: path("M4 11a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rq3kv2xzk {
  d: path("m8.5 8.5 5 5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
