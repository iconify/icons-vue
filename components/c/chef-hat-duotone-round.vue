<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="by18iwbit"/><path class="yrjyl2bni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chef-hat-duotone-round" /></template>
<style>
.by18iwbit {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 7a4 4 0 0 1 8 0c4.895-.638 6.62 6.259 2 8v2a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4v-2c-4.62-1.741-2.895-8.638 2-8");
}

.ft5dv1b6b {
  fill: none;
}

.yrjyl2bni {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 15c-4.622-1.734-2.894-8.645 2-8a4 4 0 1 1 8 0c4.894-.645 6.622 6.266 2 8v2a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4zm0 2h12");
}

</style>
