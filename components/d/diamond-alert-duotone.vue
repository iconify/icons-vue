<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vamt74boj"/><path class="e0u3qtbzv"/><path clip-rule="evenodd" class="r5rqf9usu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diamond-alert-duotone" /></template>
<style>
.e0u3qtbzv {
  d: path("M12 8V12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r5rqf9usu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 16C13 16.5523 12.5523 17 12 17C11.4477 17 11 16.5523 11 16C11 15.4477 11.4477 15 12 15C12.5523 15 13 15.4477 13 16Z");
  stroke: none;
}

.vamt74boj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.1213 18.1213L14.1213 22.1213C13.5587 22.6839 12.7956 23 12 23C11.2044 23 10.4413 22.6839 9.8787 22.1213L1.8787 14.1213C1.3161 13.5587 1 12.7956 1 12C1 11.2044 1.3161 10.4413 1.8787 9.8787L9.8787 1.8787C10.4413 1.3161 11.2044 1 12 1C12.7956 1 13.5587 1.3161 14.1213 1.8787L22.1213 9.8787C22.6839 10.4413 23 11.2044 23 12C23 12.7956 22.6839 13.5587 22.1213 14.1213Z");
  stroke: none;
}

</style>
