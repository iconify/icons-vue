<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w-pek8c8r"/><path class="elc06ob4j"/><path class="l0v-b4kbr"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grounding-outline-bold" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.elc06ob4j {
  d: path("M8 8h8");
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w-pek8c8r {
  d: path("M14 2H5v15h14V7");
}

</style>
