<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vvmflk4-r"/><path class="neb_fbd7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:exit-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.neb_fbd7g {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 17v4H3V3h18v4m-6 8l3-3l-3-3m3 3H8");
}

.vvmflk4-r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 3h18v18H3Z");
}

</style>
