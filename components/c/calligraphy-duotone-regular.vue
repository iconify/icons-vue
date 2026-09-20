<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ij4ex6enw"/><path class="mqs1sybxa"/><path class="ykenr4b4h"/><path class="y1sgy9_rm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:calligraphy-duotone-regular" /></template>
<style>
.ij4ex6enw {
  fill: currentColor;
  d: path("m13 3 4 4 -7 7 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mqs1sybxa {
  d: path("m13 3 4 4 -7 7 -4 -4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y1sgy9_rm {
  d: path("M13 20c3 -2 6 -2 8 0");
}

.ykenr4b4h {
  d: path("m8 12 -4 4v4h4l4 -4");
}

</style>
