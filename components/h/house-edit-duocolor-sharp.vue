<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h9za2-3et"/><path class="is_4m5cif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-edit-duocolor-sharp" /></template>
<style>
.h9za2-3et {
  stroke-opacity: 0.4;
  d: path("M9 17v-2l4-4l2 2l-4 4Z");
}

.is_4m5cif {
  d: path("m12 3l8 7v11H4V10z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
