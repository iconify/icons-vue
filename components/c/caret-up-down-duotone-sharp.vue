<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w5l9wy64o"/><path class="tzi-wfb5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caret-up-down-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.tzi-wfb5k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m8 10l4-4l4 4Zm0 4h8l-4 4Z");
}

.w5l9wy64o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m12 6l4 4H8Zm0 12l-4-4h8Z");
}

</style>
