<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qbtlwbt1k"/><path class="x864oibox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-ring-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qbtlwbt1k {
  stroke-opacity: 0.4;
  d: path("M17 3a9.4 9.4 0 0 1 3 3M4 6a9.4 9.4 0 0 1 3-3");
}

.x864oibox {
  d: path("M12 19H5v-2c0-1 1-1 1-2v-4a6 6 0 1 1 12 0v4c0 1 1 1 1 2v2zm-2 0a2 2 0 1 0 4 0");
}

</style>
