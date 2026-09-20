<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o0_l2fkou"/><path class="o4mkcrb3s"/><path class="i4s-lwbci"/><path class="eyp-fjbcx"/><path class="o9bf_9bzq"/><path class="qpch75bpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:body-scale-duotone-regular" /></template>
<style>
.eyp-fjbcx {
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.i4s-lwbci {
  fill: currentColor;
  d: path("M14 10h3v6h-3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o0_l2fkou {
  fill: currentColor;
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o4mkcrb3s {
  fill: currentColor;
  d: path("M7 10h3v6H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o9bf_9bzq {
  d: path("M7 10h3v6H7Z");
}

.qpch75bpm {
  d: path("M14 10h3v6h-3Z");
}

</style>
