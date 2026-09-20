<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a3hsakflq"/><path class="vslz5yb3q"/><path class="x6vx8fhgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:backpacking-outline-bold" /></template>
<style>
.a3hsakflq {
  d: path("M6 16V8a6 6 0 0 1 12 0v8Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vslz5yb3q {
  d: path("M6 12h12");
}

.x6vx8fhgp {
  d: path("M3 20.5A1.5 1.5 0 0 1 4.5 19h15a1.5 1.5 0 0 1 1.5 1.5 1.5 1.5 0 0 1 -1.5 1.5h-15A1.5 1.5 0 0 1 3 20.5");
}

</style>
