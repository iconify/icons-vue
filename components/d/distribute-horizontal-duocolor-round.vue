<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ou8j9pw5a"/><path class="kfoljqdny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-horizontal-duocolor-round" /></template>
<style>
.kfoljqdny {
  d: path("M9 9a3 3 0 0 1 6 0v6a3 3 0 0 1-6 0Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ou8j9pw5a {
  stroke-opacity: 0.4;
  d: path("M4 3v18M20 3v18");
}

</style>
