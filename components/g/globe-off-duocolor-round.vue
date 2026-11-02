<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="axcf-wb4p"/><path class="y1fmdxbwm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:globe-off-duocolor-round" /></template>
<style>
.axcf-wb4p {
  stroke-opacity: 0.4;
  d: path("m2 2l20 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y1fmdxbwm {
  d: path("M6 6c-1.629 1.629-3 3.515-3 6a9 9 0 0 0 9 9c2.485 0 4.371-1.371 6-3m3-4c.25-.827 0-1.09 0-2a9 9 0 0 0-9-9c-.91 0-1.173-.25-2 0M8 8c-.221 1.117 0 2.698 0 4c0 4.97 1.79 9 4 9m4-5c-.623 3.148-2.369 5-4 5m-9-9h9");
}

</style>
