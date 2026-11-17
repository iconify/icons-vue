<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zd7rb_ukv"/><path class="iz62silpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-loop-left-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iz62silpe {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 11a7 7 0 1 1 7 7H5m3-3l-3 3l3 3");
}

.zd7rb_ukv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 11a7 7 0 1 1 7 7H5Z");
}

</style>
