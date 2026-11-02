<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="se56--rcw"/><path class="xmso0hb8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:magic-wand-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.se56--rcw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 7c-3.75 0-4 .25-4 4c0-3.75-.25-4-4-4c3.75 0 4-.25 4-4c0 3.75.25 4 4 4");
}

.xmso0hb8r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 21l10-10m4-8c0 3.75.25 4 4 4c-3.75 0-4 .25-4 4c0-3.75-.25-4-4-4c3.75 0 4-.25 4-4M6 4v4M4 6h4m10 10v4m-2-2h4");
}

</style>
