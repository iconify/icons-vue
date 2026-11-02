<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lpateibpq"/><path class="jq7yaln0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-stacked-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jq7yaln0a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20v-9h6V4h6v4h6v12zm6 0v-9m6 9V8M3 15h6m0-3h6m0 2h6");
}

.lpateibpq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14 3a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1h-4a.997.997 0 0 1-1-1V4a1 1 0 0 1 1-1Zm8 10a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1ZM7 10a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1Zm8 10a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1Zm6-5a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1ZM2 17a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
