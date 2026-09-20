<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="duisldofr"/><path class="zmc7aqkcp"/><path class="zm6-5ikop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:customs-declare-outline-regular" /></template>
<style>
.duisldofr {
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zm6-5ikop {
  d: path("m8 17 7 -7");
}

.zmc7aqkcp {
  d: path("M9 6V3h6v3");
}

</style>
