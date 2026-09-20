<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bm4dl4toz"/><path class="l6cp2-b8s"/><path class="nib87abyv"/><path class="a7vpafiwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:box-label-duotone-thin" /></template>
<style>
.a7vpafiwa {
  d: path("M6 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.bm4dl4toz {
  fill: currentColor;
  d: path("M4 8h12l4 4 -4 4H4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l6cp2-b8s {
  fill: currentColor;
  d: path("M6 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nib87abyv {
  d: path("M4 8h12l4 4 -4 4H4Z");
}

</style>
