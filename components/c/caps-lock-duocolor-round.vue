<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fnzvalwps"/><path class="gr1fxvb3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caps-lock-duocolor-round" /></template>
<style>
.fnzvalwps {
  stroke-opacity: 0.4;
  d: path("M9 21h6");
}

.gr1fxvb3k {
  d: path("M12 17h-1a2 2 0 0 1-2-2v-2a2 2 0 0 0-2-2H6c-.738 0-1.369-.631-1-1l6-6a1.414 1.414 0 0 1 2 0l6 6c.369.369-.262 1-1 1h-1a2 2 0 0 0-2 2v2a2 2 0 0 1-2 2z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
