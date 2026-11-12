<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c__mxzcyr"/><path class="m2gfxpj_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-edit-duotone-sharp" /></template>
<style>
.c__mxzcyr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 9h16v12H4Z");
}

.ft5dv1b6b {
  fill: none;
}

.m2gfxpj_b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 5h16v16H4Zm4-2v2m8-2v2M4 9h16M9 18v-2l4-4l2 2l-4 4Z");
}

</style>
