<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s_3ouqbai"/><path class="a5a81se5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brush-duotone" /></template>
<style>
.a5a81se5s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 19v-5H8a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-2v5a2 2 0 1 1-4 0m-4-9h12m-8-7v3m4-3v3");
}

.ft5dv1b6b {
  fill: none;
}

.s_3ouqbai {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 11a1 1 0 0 1-1-1V5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v5a1 1 0 0 1-1 1Z");
}

</style>
