<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ym8p8xb-h"/><path class="f2w6xorcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gratitude-outline-regular" /></template>
<style>
.f2w6xorcc {
  d: path("M6 7a3 3 0 0 1 6 0 3 3 0 0 1 6 0l-6 6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ym8p8xb-h {
  d: path("M20 13a8 8 0 0 1 -16 0");
}

</style>
