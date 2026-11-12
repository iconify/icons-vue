<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pb5uu9bun"/><path class="a6f5g6btf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-exclude-duotone-round" /></template>
<style>
.a6f5g6btf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 9h-4a2 2 0 0 0-2 2v4H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2zm0 0h4a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2v-4h4a2 2 0 0 0 2-2z");
}

.ft5dv1b6b {
  fill: none;
}

.pb5uu9bun {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 8h3a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-8a3 3 0 0 1-3-3v-3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3Zm-6 6h3a.997.997 0 0 0 1-1v-3h-3a.997.997 0 0 0-1 1Z");
}

</style>
