<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="ms846p4ov"/><path class="g5x-39ykz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-inline-fill" /></template>
<style>
.g5x-39ykz {
  d: path("M3 3H21M3 21H21M3 12H5M19 12H21");
}

.ms846p4ov {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 8L14 8C15.1046 8 16 8.8954 16 10L16 14C16 15.1046 15.1046 16 14 16L10 16C8.8954 16 8 15.1046 8 14L8 10C8 8.8954 8.8954 8 10 8Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
