<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="njyk7_bbr"/><path class="kst16lb8k"/><path class="yjd2gm3-w"/><path class="mfoopsbgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bathtub-outline-regular" /></template>
<style>
.kst16lb8k {
  d: path("M6 18.5V21");
}

.mfoopsbgc {
  d: path("M3 11V7");
}

.njyk7_bbr {
  d: path("M3 11h18v4a4 4 0 0 1 -4 4H7a4 4 0 0 1 -4 -4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yjd2gm3-w {
  d: path("M18 18.5V21");
}

</style>
