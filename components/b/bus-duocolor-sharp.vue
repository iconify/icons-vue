<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ez2ukkb4s"/><path class="vvf61vbdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bus-duocolor-sharp" /></template>
<style>
.ez2ukkb4s {
  stroke-opacity: 0.4;
  d: path("M8 16h.01M16 16h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vvf61vbdh {
  d: path("M5 3h14v16H5zm2 16h2v2H7Zm8 0h2v2h-2ZM5 13h14M9 6h6");
}

</style>
