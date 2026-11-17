<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hm7_c0bey"/><path class="j_psw1y4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cooktop-duocolor-sharp" /></template>
<style>
.hm7_c0bey {
  stroke-opacity: 0.4;
  d: path("M6 8a2 2 0 1 1 4 0m0 0a2 2 0 1 1-4 0m8 0a2 2 0 1 1 4 0m0 0a2 2 0 1 1-4 0m-8 8a2 2 0 1 1 4 0m0 0a2 2 0 1 1-4 0m8 0a2 2 0 1 1 4 0m0 0a2 2 0 1 1-4 0");
}

.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
