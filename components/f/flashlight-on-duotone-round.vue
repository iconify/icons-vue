<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lh6scj7us"/><path class="hkz0fug3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flashlight-on-duotone-round" /></template>
<style>
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

.lh6scj7us {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17.707 10.293a2.414 2.414 0 0 1 0 3.414l-2 2C14.992 16.422 14.039 17 13 17h-1c-.468 0-.98.395-1.293.707l-3 3a2.414 2.414 0 0 1-3.414 0l-1-1a2.414 2.414 0 0 1 0-3.414l3-3C6.605 12.98 7 12.468 7 12v-1c0-1.039.578-1.992 1.293-2.707l2-2a2.414 2.414 0 0 1 3.414 0Z");
}

</style>
