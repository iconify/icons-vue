<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w_izoda_u"/><path class="xy4qp4foh"/><path class="ymbpusb5b"/><path class="epou1mbuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dog-outline-regular" /></template>
<style>
.epou1mbuy {
  d: path("M11 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w_izoda_u {
  d: path("M7 6c1 -1 3 -1 5 -1s4 0 5 1c0.5 2 0.5 5 0 7 0 4 -2 6 -5 6s-5 -2 -5 -6c-0.5 -2 -0.5 -5 0 -7");
}

.xy4qp4foh {
  d: path("M7 7c-1.5 0 -2.5 2 -2.5 5 0 2 1 3 2.5 2Z");
}

.ymbpusb5b {
  d: path("M17 7c1.5 0 2.5 2 2.5 5 0 2 -1 3 -2.5 2Z");
}

</style>
