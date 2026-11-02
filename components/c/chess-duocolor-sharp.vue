<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mli5dabdq"/><path class="l-z7x0gba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chess-duocolor-sharp" /></template>
<style>
.l-z7x0gba {
  d: path("m8 17l2-6H7L6 9l4-3l-1-3l3 1c3 1 4 4 4 7v6");
}

.mli5dabdq {
  stroke-opacity: 0.4;
  d: path("M6 17h12v4H6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
