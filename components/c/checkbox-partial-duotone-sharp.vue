<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uc3mdtb8m"/><path class="r9klxxb9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:checkbox-partial-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.r9klxxb9z {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 4h16v16H4Zm5 8h6");
}

.uc3mdtb8m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 4h16v16H4Z");
}

</style>
