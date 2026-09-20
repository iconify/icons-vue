<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l0v-b4kbr"/><path class="hm--inbem"/><path class="bu6goduan"/><path class="swt86hbgr"/><path class="gcn2u0bqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hotel-gym-outline-bold" /></template>
<style>
.bu6goduan {
  d: path("M16 7v10h3V7Z");
}

.gcn2u0bqi {
  d: path("M21.5 10v4");
}

.hm--inbem {
  d: path("M5 7v10h3V7Z");
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

.swt86hbgr {
  d: path("M2.5 10v4");
}

</style>
