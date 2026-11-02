<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vu_mukbdk"/><path class="wkt6dcbza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-check-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vu_mukbdk {
  stroke-opacity: 0.4;
  d: path("m9 10l2 2l4-4");
}

.wkt6dcbza {
  d: path("M12 4h6v16l-6-4l-6 4V4z");
}

</style>
