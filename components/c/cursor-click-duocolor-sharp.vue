<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aleqeubgz"/><path class="k9r-3cdlg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-click-duocolor-sharp" /></template>
<style>
.aleqeubgz {
  stroke-opacity: 0.4;
  d: path("M9 5V3M5 9H3m10-4l1-1m-9 9l-1 1");
}

.k9r-3cdlg {
  d: path("m9 9l12 4l-4 1l3 3l-3 3l-3-3l-1 4z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
