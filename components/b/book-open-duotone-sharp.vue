<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z0h4hg1ux"/><path class="p9q6gobzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-open-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p9q6gobzb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20V5h9v12h-6zm0 0V5H3v12h6z");
}

.z0h4hg1ux {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8.586 18H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-5.586l-2.707 2.707a1 1 0 0 1-1.414 0Z");
}

</style>
