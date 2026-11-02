<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ztt6nrbso"/><path class="xypwjta6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:handbag-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xypwjta6l {
  d: path("M5 8h14l2 12H3z");
}

.ztt6nrbso {
  stroke-opacity: 0.4;
  d: path("M8 8a4 4 0 1 1 8 0");
}

</style>
