<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ruhhfybpr"/><path class="jk_0h-bxq"/><path class="ba1a252is"/><path class="g1ah3gb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:favorite-add-duotone-regular" /></template>
<style>
.ba1a252is {
  d: path("M17.5 4.5h4");
}

.g1ah3gb0p {
  d: path("M19.5 2.5v4");
}

.jk_0h-bxq {
  d: path("M4 11a4 4 0 0 1 8 0 4 4 0 0 1 8 0l-8 8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ruhhfybpr {
  fill: currentColor;
  d: path("M4 11a4 4 0 0 1 8 0 4 4 0 0 1 8 0l-8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
