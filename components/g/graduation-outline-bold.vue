<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n6wz72bec"/><path class="s-lluab2i"/><path class="vtt_9-b1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:graduation-outline-bold" /></template>
<style>
.n6wz72bec {
  d: path("m2 10 4 -4h12l4 4 -4 4H6Z");
}

.s-lluab2i {
  d: path("M8 14v3l3 3h3l3 -3v-3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vtt_9-b1s {
  d: path("M22 10v6");
}

</style>
