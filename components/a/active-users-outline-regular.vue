<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q8-0ejn0y"/><path class="igyz-cc5b"/><path class="pt73j1ikv"/><path class="mlfk3xi6j"/><path class="y4qjbbcmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:active-users-outline-regular" /></template>
<style>
.igyz-cc5b {
  d: path("M3 20a5 5 0 0 1 10 0");
}

.mlfk3xi6j {
  d: path("M18 10v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pt73j1ikv {
  d: path("M15 14v6");
}

.q8-0ejn0y {
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.y4qjbbcmm {
  d: path("M21 6v14");
}

</style>
