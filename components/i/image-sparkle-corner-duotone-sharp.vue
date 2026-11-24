<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zexmunqdv"/><path class="a_bfsab7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-sparkle-corner-duotone-sharp" /></template>
<style>
.a_bfsab7j {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 21H3V3h18v8M3 17l6-6l2 2m3-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m4 7c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

.ft5dv1b6b {
  fill: none;
}

.zexmunqdv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 3v8H11v10H3V3Zm-3 12c.002 1.005 1.995 2.998 3 3c-1.005.002-2.998 1.995-3 3c-.002-1.005-1.995-2.998-3-3c1.005-.002 2.998-1.995 3-3");
}

</style>
