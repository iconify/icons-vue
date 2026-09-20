<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c8h3t-z9z"/><path class="y80g12bwz"/><path class="jbmfbdcwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dairy-free-outline-bold" /></template>
<style>
.c8h3t-z9z {
  d: path("M7 9v11h9V9Z");
}

.jbmfbdcwk {
  d: path("M4 21 20 5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y80g12bwz {
  d: path("m7 9 4.5 -4.5L16 9");
}

</style>
