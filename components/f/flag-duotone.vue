<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pwrqphzgr"/><path class="pvpan2bmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flag-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pvpan2bmj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 15c6-3 10 3 16 0V4C14 7 10 1 4 4Zm0 0v6");
}

.pwrqphzgr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 15V4c3-1.5 5.5-.75 8 0s5 1.5 8 0v11c-3 1.5-5.5.75-8 0s-5-1.5-8 0");
}

</style>
