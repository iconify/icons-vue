<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cynyi85ab"/><path class="k9k9pkbqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-download-corner-duotone-round" /></template>
<style>
.cynyi85ab {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 12c-.796 0-1.559.316-2.121.879A3 3 0 0 0 12 15v6a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v4a1 1 0 0 1-1 1Z");
}

.ft5dv1b6b {
  fill: none;
}

.k9k9pkbqj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 21H7a4 4 0 0 1-4-4V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v4M3 17l4-4a2.83 2.83 0 0 1 4 0m3-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 10l3 3l3-3m-3 3v-6");
}

</style>
