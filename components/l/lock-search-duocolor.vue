<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mx73lcb8b"/><path class="v_hhlyzfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-search-duocolor" /></template>
<style>
.mx73lcb8b {
  stroke-opacity: 0.4;
  d: path("M9 14a2 2 0 1 0 4 0a2 2 0 0 0-4 0m4 2l2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v_hhlyzfc {
  d: path("M4 11a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2Zm4-2V7a4 4 0 1 1 8 0v2");
}

</style>
