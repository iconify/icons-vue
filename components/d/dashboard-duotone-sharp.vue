<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x72nkbu9l"/><path class="sllbwv1tb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dashboard-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.sllbwv1tb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 4h6v8H4Zm0 12h6v4H4Zm10-4h6v8h-6Zm0-8h6v4h-6Z");
}

.x72nkbu9l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 4v8H4V4Zm10 0v4h-6V4Zm0 8v8h-6v-8Zm-10 4v4H4v-4Z");
}

</style>
