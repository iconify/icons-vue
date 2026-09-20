<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k4zaewbkp"/><path class="zau75m19k"/><path class="c_mfsp6hl"/><path class="urs2k1bvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:canary-token-outline-regular" /></template>
<style>
.c_mfsp6hl {
  d: path("M18.12 10.88a3 3 0 0 1 0 4.24");
}

.k4zaewbkp {
  d: path("M3 9h9l4 4 -4 4H3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.urs2k1bvo {
  d: path("M20.24 8.76a6 6 0 0 1 0 8.5");
}

.zau75m19k {
  d: path("M5 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
