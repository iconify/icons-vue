<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b4ql3fbzm"/><path class="mnjdjjcri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:graphics-card-duotone-round" /></template>
<style>
.b4ql3fbzm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 4h12a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V8a4 4 0 0 1 4-4");
}

.ft5dv1b6b {
  fill: none;
}

.mnjdjjcri {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Zm0-5v18m4-4v3a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1v-3M6 11a2 2 0 1 0 4 0a2 2 0 0 0-4 0m8 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
