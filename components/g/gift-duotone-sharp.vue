<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u7n4dcbht"/><path class="k_1-sabsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gift-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k_1-sabsw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7h18v4H3Zm2 4v10h14V11m-7-4H9C7 7 6 6 6 5c0-2 2-2 3-1zm0 0h3c2 0 3-1 3-2c0-2-2-2-3-1zm0 0v14");
}

.u7n4dcbht {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 6a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-1v9a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-9H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1Z");
}

</style>
