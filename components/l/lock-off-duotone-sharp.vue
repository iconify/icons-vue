<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q7h0ut23o"/><path class="nn11so-0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-off-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nn11so-0d {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 21H4V9h4m6 0h6v6M9.172 4.172A4 4 0 0 1 16 7v2M2 3l19 19");
}

.q7h0ut23o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 21V9h4l12 12ZM14 9h6v6Z");
}

</style>
