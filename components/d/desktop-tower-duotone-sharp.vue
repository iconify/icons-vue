<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j-ypkl0-i"/><path class="fra9j4bti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:desktop-tower-duotone-sharp" /></template>
<style>
.fra9j4bti {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 4h8v16h-8Zm0 5H3v8h10m4-9h.01M17 13v3M6 20h3");
}

.ft5dv1b6b {
  fill: none;
}

.j-ypkl0-i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 4h8v16h-8Z");
}

</style>
