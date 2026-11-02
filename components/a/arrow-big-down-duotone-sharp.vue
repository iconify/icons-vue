<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u551brufx"/><path class="enw7kxfof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-down-duotone-sharp" /></template>
<style>
.enw7kxfof {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4H9v8H4l8 8l8-8h-5V4z");
}

.ft5dv1b6b {
  fill: none;
}

.u551brufx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 4h6v8h5l-8 8l-8-8h5Z");
}

</style>
