<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mbn-n19qn"/><path class="ddgzt92rv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-export-duotone" /></template>
<style>
.ddgzt92rv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12V7.066a1 1 0 0 0-.557-.897L16.5 4.222m0 0L12.443 2.22a1 1 0 0 0-.886 0l-8 3.95A1 1 0 0 0 3 7.066v9.868a1 1 0 0 0 .557.897l7.546 3.726A.62.62 0 0 0 12 21V10.889M3.16 6.523L12 10.89l8.84-4.366M18 21l3-3l-3-3m3 3h-6");
}

.ft5dv1b6b {
  fill: none;
}

.mbn-n19qn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 11.51V21a1.62 1.62 0 0 1-2.339 1.454l-7.547-3.727A2 2 0 0 1 2 16.934V7.066a2 2 0 0 1 1.114-1.793l8-3.951a2 2 0 0 1 1.772 0l7.66 3.783a1.494 1.494 0 0 1 0 2.679Z");
}

</style>
