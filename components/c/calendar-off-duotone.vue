<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xs-463idv"/><path class="osjl4y2tb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.osjl4y2tb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 20c-.314.694-1.189 1-2 1H6a2 2 0 0 1-2-2V7c0-.811.306-1.686 1-2m6 0h7a2 2 0 0 1 2 2v7M4 9h5m6 0h5m-4-6v2M2 2l20 20");
}

.xs-463idv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 10a1 1 0 0 1-1-1V7a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1Z");
}

</style>
