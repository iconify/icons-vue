<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vvoe99wrk"/><path class="tprfi6wge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hammer-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.tprfi6wge {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 3l1 1c1.28 1.28 2 2.72 2 4v2l2 2h2l2 2l3-3l-2-2V7l-2-2c-1.28-1.28-2.72-2-4-2zm6 9l-8 8a2.121 2.121 0 1 1-3-3l8-8");
}

.vvoe99wrk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3.293 16.293L11 8.586V8c0-1.232-.873-2.459-1.707-3.293l-1-1A1 1 0 0 1 9 2h4c1.804 0 3.47 1.056 4.707 2.293l2 2A1 1 0 0 1 20 7v1.586l1.707 1.707a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414 0L15.586 13h-.172l-7.707 7.707a3.121 3.121 0 1 1-4.414-4.414");
}

</style>
