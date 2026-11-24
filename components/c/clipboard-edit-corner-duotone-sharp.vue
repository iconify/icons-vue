<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bfaqdgb5f"/><path class="b65h1yobc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-edit-corner-duotone-sharp" /></template>
<style>
.b65h1yobc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 5H5v16h4M19 9V5h-4M9 5V3h6v2M9 5v2h6V5m-2 16v-3l5-5l3 3l-5 5Z");
}

.bfaqdgb5f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 5v4H9v12H5V5Zm-6 13l5-5l3 3l-5 5h-3Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
