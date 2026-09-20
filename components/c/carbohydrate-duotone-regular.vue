<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jqdvcpneq"/><path class="cbe4yor0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:carbohydrate-duotone-regular" /></template>
<style>
.cbe4yor0z {
  d: path("M5 20v-9a4 4 0 0 1 4 -4h6a4 4 0 0 1 4 4v9Z");
}

.jqdvcpneq {
  fill: currentColor;
  d: path("M5 20v-9a4 4 0 0 1 4 -4h6a4 4 0 0 1 4 4v9Z");
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

</style>
