<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d4_jtmtlt"/><path class="hkz0fug3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flashlight-on-duotone-round" /></template>
<style>
.d4_jtmtlt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m13 7l4 4a1.415 1.415 0 0 1 0 2l-2 2c-.521.52-1.237 1-2 1h-1c-.763 0-1.479.48-2 1l-3 3a1.415 1.415 0 0 1-2 0l-1-1a1.415 1.415 0 0 1 0-2l3-3c.52-.521 1-1.237 1-2v-1c0-.763.48-1.479 1-2l2-2a1.415 1.415 0 0 1 2 0");
}

.ft5dv1b6b {
  fill: none;
}

.hkz0fug3q {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 9l2 2a1.414 1.414 0 0 1 0 2l-2 2c-.64.64-1.36 1-2 1h-1c-.64 0-1.36.36-2 1l-3 3a1.414 1.414 0 0 1-2 0l-1-1a1.414 1.414 0 0 1 0-2l3-3c.64-.64 1-1.36 1-2v-1c0-.64.36-1.36 1-2l2-2a1.414 1.414 0 0 1 2 0zM9 9l6 6m1-12v2m3 0l2-2m-2 5h2");
}

</style>
