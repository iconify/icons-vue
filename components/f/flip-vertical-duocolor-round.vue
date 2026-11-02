<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hir2rd3zm"/><path class="kp9s7d_6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-duocolor-round" /></template>
<style>
.hir2rd3zm {
  stroke-opacity: 0.4;
  d: path("M12 21H9c-.738 0-1.369-.631-1-1l3-3a1.414 1.414 0 0 1 2 0l3 3c.369.369-.262 1-1 1z");
}

.kp9s7d_6g {
  d: path("M12 3H9c-.738 0-1.369.631-1 1l3 3a1.414 1.414 0 0 0 2 0l3-3c.369-.369-.262-1-1-1zm-7 9h2m4 0h2m4 0h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
