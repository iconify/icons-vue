<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ictsdupji"/><path class="b275f7mjg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-keyhole-duotone-round" /></template>
<style>
.b275f7mjg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 14a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v3a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm7 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 1v3m-3-8V6a3 3 0 0 1 6 0v4");
}

.ft5dv1b6b {
  fill: none;
}

.ictsdupji {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 9h8a5 5 0 0 1 5 5v3a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5v-3a5 5 0 0 1 5-5");
}

</style>
