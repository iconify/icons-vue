<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a3fayfb3t"/><path class="bcoat1b-j"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:high-speed-train-outline-regular" /></template>
<style>
.a3fayfb3t {
  d: path("M2 18v-6l7 -7h9a2 2 0 0 1 2 2v11Z");
}

.bcoat1b-j {
  d: path("M9 12h11");
}

.bos0j4biy {
  d: path("M3 21h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
