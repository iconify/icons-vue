<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wkfr7rb1b"/><path class="si9j86b3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hammer-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.si9j86b3j {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 3l1 1c1.28 1.28 2 2.72 2 4v2l2 2h1c.64 0 1.36.36 2 1a1.414 1.414 0 0 0 2 0l1-1a1.414 1.414 0 0 0 0-2c-.64-.64-1-1.36-1-2s-.36-1.36-1-2l-1-1c-1.28-1.28-2.72-2-4-2zm6 9l-8 8a2.121 2.121 0 1 1-3-3l8-8");
}

.wkfr7rb1b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 20a2.122 2.122 0 0 1-3-3l8-8V8c-.001-1.52-.964-2.963-2-4L9 3h4c1.52.001 2.963.964 4 2l1 1c.52.521 1 1.237 1 2s.48 1.479 1 2a1.415 1.415 0 0 1 0 2l-1 1a1.415 1.415 0 0 1-2 0c-.521-.52-1.237-1-2-1Z");
}

</style>
