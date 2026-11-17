<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cfrj5tb9l"/><path class="ipgerybnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-click-duotone-sharp" /></template>
<style>
.cfrj5tb9l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m9 9l12 4l-4 1l3 3l-3 3l-3-3l-1 4Z");
}

.ft5dv1b6b {
  fill: none;
}

.ipgerybnw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 9l12 4l-4 1l3 3l-3 3l-3-3l-1 4zm0-4V3M5 9H3m10-4l1-1m-9 9l-1 1");
}

</style>
