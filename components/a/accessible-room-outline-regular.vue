<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m0-fu-bsn"/><path class="n0v-0cb9k"/><path class="d63s22xct"/><path class="nk-dq3bmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:accessible-room-outline-regular" /></template>
<style>
.d63s22xct {
  d: path("M6 17a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.m0-fu-bsn {
  d: path("M7 4.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n0v-0cb9k {
  d: path("M9 7v7h7");
}

.nk-dq3bmo {
  d: path("m16 14 3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
