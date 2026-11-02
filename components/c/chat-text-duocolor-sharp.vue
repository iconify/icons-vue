<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="font_abim"/><path class="kwh_pwbjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-text-duocolor-sharp" /></template>
<style>
.font_abim {
  stroke-opacity: 0.4;
  d: path("M8 8h8m-8 4h5");
}

.kwh_pwbjw {
  d: path("M12 17H7l-4 4V3h18v14z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
