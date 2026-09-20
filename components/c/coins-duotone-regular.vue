<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i2n0f_wdy"/><path class="e7kusactt"/><path class="d9oh1gxrx"/><path class="n32o5nlfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coins-duotone-regular" /></template>
<style>
.d9oh1gxrx {
  d: path("M4 13a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.e7kusactt {
  fill: currentColor;
  d: path("M10 11a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.i2n0f_wdy {
  fill: currentColor;
  d: path("M4 13a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n32o5nlfd {
  d: path("M10 11a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
