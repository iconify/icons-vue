<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tsevlt2dd"/><path class="wj4ljftik"/><path class="jtmtyidol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:butter-outline-bold" /></template>
<style>
.jtmtyidol {
  d: path("M3 16h18c0 3 -4 5 -9 5s-9 -2 -9 -5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tsevlt2dd {
  d: path("M6 7v6h12V7Z");
}

.wj4ljftik {
  d: path("M10 7v6");
}

</style>
