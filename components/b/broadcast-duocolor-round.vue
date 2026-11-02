<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xrvxr8byk"/><path class="x9ahn40kq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:broadcast-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x9ahn40kq {
  d: path("M12 12h.01");
}

.xrvxr8byk {
  stroke-opacity: 0.4;
  d: path("M15 9a4.243 4.243 0 0 1 0 6m3-9a8.485 8.485 0 0 1 0 12m-9-3a4.243 4.243 0 0 1 0-6m-3 9A8.485 8.485 0 0 1 6 6");
}

</style>
