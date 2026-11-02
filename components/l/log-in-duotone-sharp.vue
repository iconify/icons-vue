<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gmz709yrs"/><path class="gf4_-obgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:log-in-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gf4_-obgb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 7V3h11v18H8v-4m4-2l3-3m0 0l-3-3m3 3H5");
}

.gmz709yrs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 3h11v18H8Z");
}

</style>
