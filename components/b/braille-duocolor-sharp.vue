<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rx6hxmjuz"/><path class="ypxmn0p_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:braille-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rx6hxmjuz {
  stroke-opacity: 0.4;
  d: path("M8 12h.01M16 4h.01M16 20h.01");
}

.ypxmn0p_z {
  d: path("M7 4a1 1 0 1 0 2 0a1 1 0 0 0-2 0m0 16a1 1 0 1 0 2 0a1 1 0 0 0-2 0m8-8a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
