<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qk8jf1izq"/><path class="tdvfme0qd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brush-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qk8jf1izq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 11a1 1 0 0 1-1-1V7a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v3a1 1 0 0 1-1 1Z");
}

.tdvfme0qd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 19v-5H8a2 2 0 0 1-2-2V7a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v5a2 2 0 0 1-2 2h-2v5a2 2 0 1 1-4 0m-4-9h12m-8-7v3m4-3v3");
}

</style>
