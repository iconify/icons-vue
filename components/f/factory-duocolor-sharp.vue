<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jw8scnbdr"/><path class="d72lznopt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:factory-duocolor-sharp" /></template>
<style>
.d72lznopt {
  d: path("M3 21h18M5 21V3h4v9l5-3v3l5-3v12");
}

.jw8scnbdr {
  stroke-opacity: 0.4;
  d: path("M8 16h.01M12 16h.01M16 16h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
