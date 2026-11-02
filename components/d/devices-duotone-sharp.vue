<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lxnh5fbtr"/><path class="g77n7_nql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:devices-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g77n7_nql {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 10h6v10h-6Zm2-4V4H3v12h8");
}

.lxnh5fbtr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 10h6v10h-6Z");
}

</style>
