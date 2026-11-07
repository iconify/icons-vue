<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p52u7fomt"/><path class="l6krpxbux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-off-duocolor-round" /></template>
<style>
.l6krpxbux {
  d: path("M18 19H7A5 5 0 0 1 7 9q.112-.39.252-.748m2.726-3.274C13.338 3.11 18 5.242 18 11a4 4 0 0 1 3.646 5.647");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p52u7fomt {
  stroke-opacity: 0.4;
  d: path("m2 3l19 19");
}

</style>
