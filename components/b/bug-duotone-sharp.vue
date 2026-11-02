<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t8rbvetgb"/><path class="qcb-798lm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bug-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qcb-798lm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 13V7H7v6a5 5 0 0 0 10 0M9 7a3 3 0 0 1 6 0m-3 4v7m-5-7L4 8m3 5H3m5 3l-3 3m12-8l3-3m-3 5h4m-5 3l3 3");
}

.t8rbvetgb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15.874 6H17a1 1 0 0 1 1 1v6a6 6 0 1 1-12 0V7a1 1 0 0 1 1-1h1.126a4 4 0 0 1 7.748 0");
}

</style>
