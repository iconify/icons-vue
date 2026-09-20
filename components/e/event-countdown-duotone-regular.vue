<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="drv76mblh"/><path class="rl--ddclc"/><path class="di4dnkbvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-countdown-duotone-regular" /></template>
<style>
.di4dnkbvr {
  d: path("M8 19c1.5 -2 6.5 -2 8 0");
}

.drv76mblh {
  fill: currentColor;
  d: path("M6 3h12c0 4 -5 6 -5 9s5 5 5 9H6c0 -4 5 -6 5 -9S6 7 6 3");
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

.rl--ddclc {
  d: path("M6 3h12c0 4 -5 6 -5 9s5 5 5 9H6c0 -4 5 -6 5 -9S6 7 6 3");
}

</style>
