<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sy4eus42g"/><path class="hy2-9ybvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:heart-rate-outline-regular" /></template>
<style>
.hy2-9ybvg {
  d: path("M2 13h6l2 -2 4 4 2 -2h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sy4eus42g {
  d: path("M4 10a4 4 0 0 1 8 0 4 4 0 0 1 8 0l-8 8Z");
}

</style>
