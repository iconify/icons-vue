<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jhq2fxlof"/><path class="rsvh7b0ab"/><path class="uk_l5kxob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:eraser-outline-regular" /></template>
<style>
.jhq2fxlof {
  d: path("m3 15 6 -6h12l-6 6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rsvh7b0ab {
  d: path("M3 15v4h12l6 -6V9");
}

.uk_l5kxob {
  d: path("M9 9v4l-6 6");
}

</style>
