<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="km-j3eb9k"/><path class="r8i1ocbvm"/><path class="hzt89hucj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:access-point" /></template>
<style>
.hzt89hucj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 9.25a5 5 0 0 1 6.5 0m-9.5-3.5a9.5 9.5 0 0 1 12.5 0");
}

.km-j3eb9k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 18.25a8.25 5 0 0 1 16.5 0v.5a2 2 0 0 1-2 2H5.75a2 2 0 0 1-2-2Z");
}

.r8i1ocbvm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
