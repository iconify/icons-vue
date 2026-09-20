<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jzfjzbcmq"/><path class="g_w90ac2s"/><path class="l-37rlmum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:interpretability-outline-bold" /></template>
<style>
.g_w90ac2s {
  d: path("M10 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.jzfjzbcmq {
  d: path("M14 3h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V6l3 -3h3");
}

.l-37rlmum {
  d: path("m17 18 3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
