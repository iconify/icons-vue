<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qrnco0m4y"/><path class="z-u-ue7vh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-edit-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qrnco0m4y {
  stroke-opacity: 0.4;
  d: path("M15 21v-2l4-4l2 2l-4 4Z");
}

.z-u-ue7vh {
  d: path("M19 11a8 8 0 1 0-8 8m0-12v4h3");
}

</style>
