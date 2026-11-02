<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r9qaelaaf"/><path class="py9jam25n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:filter-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py9jam25n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h7a1 1 0 0 1 1 1c0 .64-.36 1.36-1 2l-2 2m-3 3c-.117.28 0 .736 0 1v4c0 .613-.774 1.387-2 2c-.919.46-2-.081-2-1v-5c0-.64-.36-1.36-1-2L5 7c-.64-.64-1-1.36-1-2a1 1 0 0 1 1-1h1M4 2l14 14");
}

.r9qaelaaf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 3c.531 0 1.039.21 1.414.586c.791.791.691 1.92.221 2.861c-.235.469-.558.89-.928 1.26l-4 4C15.395 12.02 15 12.532 15 13v4c-.001 1.348-1.478 2.357-2.553 2.894c-1.057.529-2.418.28-3.095-.729A2.1 2.1 0 0 1 9 18v-5c0-.468-.395-.98-.707-1.293l-4-4a4.9 4.9 0 0 1-.928-1.26c-.47-.941-.57-2.07.221-2.861A2 2 0 0 1 5 3Z");
}

</style>
