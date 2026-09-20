<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y-c_3vbcr"/><path class="grk37x-os"/><path class="f9zkr6_8j"/><path class="kscrclbnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:communication-outline-regular" /></template>
<style>
.f9zkr6_8j {
  d: path("M9 17a4 4 0 0 1 4 -4h5a4 4 0 0 1 4 4 4 4 0 0 1 -4 4h-5a4 4 0 0 1 -4 -4");
}

.grk37x-os {
  d: path("M5 11v3l3 -3");
}

.kscrclbnc {
  d: path("M19 13v-3l-3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y-c_3vbcr {
  d: path("M2 7a4 4 0 0 1 4 -4h5a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H6a4 4 0 0 1 -4 -4");
}

</style>
