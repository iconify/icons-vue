<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eext-rbov"/><path class="sx1yrbcdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-help-duotone-sharp" /></template>
<style>
.eext-rbov {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 4h7l2 2h9v14H3Z");
}

.ft5dv1b6b {
  fill: none;
}

.sx1yrbcdx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h9v14H3V4h7zm-2 6a2 2 0 1 1 2 2m0 3h.01");
}

</style>
