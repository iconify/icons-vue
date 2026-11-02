<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nii8x_bfq"/><path class="kwh_pwbjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-heart-duocolor-sharp" /></template>
<style>
.kwh_pwbjw {
  d: path("M12 17H7l-4 4V3h18v14z");
}

.nii8x_bfq {
  stroke-opacity: 0.4;
  d: path("M12 9c-1-2-4-2-4 0s4 4 4 4s4-2 4-4s-3-2-4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
