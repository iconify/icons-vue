<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cxu5sjb1s"/><path class="dzba6hbol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:loop-duotone-sharp" /></template>
<style>
.cxu5sjb1s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 6h18v12H3Z");
}

.dzba6hbol {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 18h6V6H3v12h8m-3 3l3-3l-3-3");
}

.ft5dv1b6b {
  fill: none;
}

</style>
