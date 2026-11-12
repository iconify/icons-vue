<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p_5-o3uqe"/><path class="v34ymiblw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:data-packet-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p_5-o3uqe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 4h4a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20h-4a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5");
}

.v34ymiblw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4Zm0 0h12m-8 4v3m4-3v3M3 8h2m-2 4h2m-2 4h2");
}

</style>
