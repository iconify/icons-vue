<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tfw3n8bht"/><path class="kwh_pwbjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-minus-duocolor-sharp" /></template>
<style>
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

.tfw3n8bht {
  stroke-opacity: 0.4;
  d: path("M9 10h6");
}

</style>
