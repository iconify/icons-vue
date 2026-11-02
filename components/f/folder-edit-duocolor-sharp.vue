<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ckpl17b5l"/><path class="og2hi81sh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-edit-duocolor-sharp" /></template>
<style>
.ckpl17b5l {
  stroke-opacity: 0.4;
  d: path("M9 16v-2l4-4l2 2l-4 4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.og2hi81sh {
  d: path("M12 6h9v14H3V4h7z");
}

</style>
