<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ozaflpbkf"/><path class="qft37d97h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bulb-sparkle-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ozaflpbkf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 18H9v-3c0-1.5-3-3.5-3-6a6 6 0 1 1 12 0c0 2.5-3 4.5-3 6Z");
}

.qft37d97h {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 15v3H9v-3c0-1.5-3-3.5-3-6a6 6 0 1 1 12 0c0 2.5-3 4.5-3 6m-6 6h6M12 6c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

</style>
