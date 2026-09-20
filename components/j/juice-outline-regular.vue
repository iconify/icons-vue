<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rh6cspb3h"/><path class="l2k0-c9-j"/><path class="xj_kqitvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:juice-outline-regular" /></template>
<style>
.l2k0-c9-j {
  d: path("m6 8 5 -5 5 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rh6cspb3h {
  d: path("M6 8v13h10V8Z");
}

.xj_kqitvx {
  d: path("m13 8 5 -5");
}

</style>
