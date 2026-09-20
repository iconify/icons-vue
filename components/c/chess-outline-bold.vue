<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mu5pjkbqo"/><path class="rnv77s7xr"/><path class="it0a8bbrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chess-outline-bold" /></template>
<style>
.it0a8bbrp {
  d: path("M14 14h3v3h-3Z");
}

.mu5pjkbqo {
  d: path("M3 3v18h18V3Z");
}

.rnv77s7xr {
  d: path("M7 7h3v3H7Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
