<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c__mxzcyr"/><path class="wyjf21cly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-days-duotone-sharp" /></template>
<style>
.c__mxzcyr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 9h16v12H4Z");
}

.ft5dv1b6b {
  fill: none;
}

.wyjf21cly {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 5h16v16H4Zm4-2v2m8-2v2M4 9h16M8 13h.01M8 17h.01M12 13h.01M12 17h.01M16 13h.01M16 17h.01");
}

</style>
