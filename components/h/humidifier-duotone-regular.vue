<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bwit_lbla"/><path class="kqvdx1b2z"/><path class="l0v-b4kbr"/><path class="yo7qm2b6k"/><path class="u3lgeqbys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:humidifier-duotone-regular" /></template>
<style>
.bwit_lbla {
  fill: currentColor;
  d: path("M6 11a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kqvdx1b2z {
  d: path("M6 11a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u3lgeqbys {
  d: path("M14 6c0 -2 2 -2 2 -4");
}

.yo7qm2b6k {
  d: path("M9 6c0 -2 2 -2 2 -4");
}

</style>
