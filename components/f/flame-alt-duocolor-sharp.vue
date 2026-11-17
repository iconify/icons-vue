<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h5wpkvbcs"/><path class="uf9zgowqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flame-alt-duocolor-sharp" /></template>
<style>
.h5wpkvbcs {
  stroke-opacity: 0.4;
  d: path("M10.5 21C6 17.5 8 14.5 12 11c4 3.5 6 6.5 1.5 10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uf9zgowqx {
  d: path("M10.5 21C2 14 8 8 12 3c4 5 10 11 1.5 18Z");
}

</style>
