<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nb2b_dbii"/><path class="k3hxzxbpv"/><path class="lvg3yfbgk"/><path class="d3t8z9b-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bedtime-duotone-bold" /></template>
<style>
.d3t8z9b-e {
  d: path("M14 2a5 5 0 1 0 0 10 4 4 0 0 1 0 -10");
}

.k3hxzxbpv {
  fill: currentColor;
  d: path("M14 2a5 5 0 1 0 0 10 4 4 0 0 1 0 -10");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lvg3yfbgk {
  d: path("M3 18a3 3 0 0 1 0 -6h18a3 3 0 0 1 0 6Z");
}

.nb2b_dbii {
  fill: currentColor;
  d: path("M3 18a3 3 0 0 1 0 -6h18a3 3 0 0 1 0 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
