<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tk5lf8bih"/><path class="b68bgeleh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-minus-corner-duocolor-round" /></template>
<style>
.b68bgeleh {
  d: path("M11 21H8a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4h8a4 4 0 0 1 3.464 2M8 9V7a4 4 0 1 1 8 0v2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tk5lf8bih {
  stroke-opacity: 0.4;
  d: path("M15 17h6");
}

</style>
