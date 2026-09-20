<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vrwd8ac_j"/><path class="vsc_xuipx"/><path class="c27cgq4un"/><path class="jlfl_ccwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-create-duotone-regular" /></template>
<style>
.c27cgq4un {
  d: path("M18 8v8");
}

.jlfl_ccwj {
  d: path("M14 12h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vrwd8ac_j {
  fill: currentColor;
  d: path("M2 7h12v3l-2 2 2 2v3H2v-3l2 -2 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vsc_xuipx {
  d: path("M2 7h12v3l-2 2 2 2v3H2v-3l2 -2 -2 -2Z");
}

</style>
