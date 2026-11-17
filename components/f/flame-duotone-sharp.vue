<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jycajs_xf"/><path class="bus8ftb2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flame-duotone-sharp" /></template>
<style>
.bus8ftb2b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3c.5 2.5 2 4.5 4 6c1.5 1.5 2 3.5 2 6a6 6 0 1 1-12 0c0-1.5.5-2.5 1-3m0 0a2 2 0 1 0 4 0c0-1.5-.5-2-1-3c-1-2-.5-4 2-6");
}

.ft5dv1b6b {
  fill: none;
}

.jycajs_xf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 3c.498 2.486 1.998 4.498 4 6c1.618 1.62 2 3.795 2 6a6 6 0 1 1-12 0c0-1.019.252-2.251 1-3a2 2 0 1 0 4 0c0-1.5-.5-2-1-3c-1.226-2.456.053-4.441 2-6");
}

</style>
