<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ddlcevtmi"/><path class="sbzy7l3ov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:key-duotone-sharp" /></template>
<style>
.ddlcevtmi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 21a5 5 0 1 1 .001-10.001A5 5 0 0 1 8 21");
}

.ft5dv1b6b {
  fill: none;
}

.sbzy7l3ov {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 12l9-9M3 16a5 5 0 1 0 10 0a5 5 0 0 0-10 0m13-8l2 2m1-5l2 2");
}

</style>
