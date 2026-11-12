<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gjch-sutj"/><path class="iny4f4bzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-cherry-pick-duocolor-round" /></template>
<style>
.gjch-sutj {
  stroke-opacity: 0.4;
  d: path("M12 6c2-3 6-3 8 0c-1 1-3 2-4 2s-3-1-4-2");
}

.iny4f4bzk {
  d: path("M3 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m14 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0M5 16c0-5 3-10 7-10m7 10c0-3-1-6-3-8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
