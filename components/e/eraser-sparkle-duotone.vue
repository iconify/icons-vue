<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t_c6ygb2c"/><path class="ycda45bkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-sparkle-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.t_c6ygb2c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 3c.002 1.005 1.995 2.998 3 3c-1.005.002-2.998 1.995-3 3c-.002-1.005-1.995-2.998-3-3c1.005-.002 2.998-1.995 3-3M5 16L15 6a1.415 1.415 0 0 1 2 0l3 3a1.415 1.415 0 0 1 0 2l-9 9H7l-2-2a1.415 1.415 0 0 1 0-2");
}

.ycda45bkz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 16l5-5a1.414 1.414 0 0 0 0-2l-3-3a1.414 1.414 0 0 0-2 0l-5 5m0 0l-5 5a1.414 1.414 0 0 0 0 2l2 2h4l4-4m-4 4h10m-11-9l5 5M6 3c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

</style>
