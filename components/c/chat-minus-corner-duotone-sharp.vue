<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ri5owy26v"/><path class="k-0c06bmb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-minus-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k-0c06bmb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 17H7l-4 4V3h18v6m-8 7h8");
}

.ri5owy26v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 9H9v8H7l-4 4V3h18Z");
}

</style>
