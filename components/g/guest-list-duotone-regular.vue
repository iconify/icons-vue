<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l51r-wb3s"/><path class="z7wppxt9k"/><path class="ce80bno8x"/><path class="qvytntb8g"/><path class="c6uw-ccfl"/><path class="f8arnkt8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:guest-list-duotone-regular" /></template>
<style>
.c6uw-ccfl {
  d: path("M7 14h10");
}

.ce80bno8x {
  d: path("M9 5V2h6v3");
}

.f8arnkt8y {
  d: path("M7 18h6");
}

.l51r-wb3s {
  fill: currentColor;
  d: path("M4 5v16h16V5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qvytntb8g {
  d: path("M7 10h10");
}

.z7wppxt9k {
  d: path("M4 5v16h16V5Z");
}

</style>
