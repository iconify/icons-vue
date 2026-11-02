<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lln0f3f1b"/><path class="gvxpuy-zj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-plus-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gvxpuy-zj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 3h14v14H7ZM3 9v12h12m-4-11h6m-3-3v6");
}

.lln0f3f1b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 3h14v14H7Z");
}

</style>
