<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a9fmp_b2b"/><path class="hwnynfbiz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-todo-duotone-sharp" /></template>
<style>
.a9fmp_b2b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 4h6v6H3Z");
}

.ft5dv1b6b {
  fill: none;
}

.hwnynfbiz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 7h8m-8 10h8M3 4h6v6H3Zm0 13l2 2l4-4");
}

</style>
