<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fdqwpiaik"/><path class="kp3yo5bal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cassette-duocolor-sharp" /></template>
<style>
.fdqwpiaik {
  stroke-opacity: 0.4;
  d: path("M6 10a2 2 0 1 0 4 0a2 2 0 0 0-4 0m8 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.kp3yo5bal {
  d: path("M3 5h18v14H3Zm4 14l2-4h6l2 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
