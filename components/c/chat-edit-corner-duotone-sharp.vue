<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t67-797is"/><path class="vlf-abosn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-edit-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.t67-797is {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 9v8H7l-4 4V3h18v6Zm4 12v-3l5-5l3 3l-5 5Z");
}

.vlf-abosn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 17H7l-4 4V3h18v6m-8 12v-3l5-5l3 3l-5 5Z");
}

</style>
