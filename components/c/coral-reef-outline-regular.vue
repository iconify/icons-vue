<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gdxs68qsm"/><path class="utps5obsq"/><path class="axphtybjp"/><path class="r1wy_ibgj"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coral-reef-outline-regular" /></template>
<style>
.axphtybjp {
  d: path("M15 21V9l-3 -3");
}

.bos0j4biy {
  d: path("M3 21h18");
}

.gdxs68qsm {
  d: path("M7 21v-9L4 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r1wy_ibgj {
  d: path("m15 13 4 -4");
}

.utps5obsq {
  d: path("m7 15 4 -4");
}

</style>
