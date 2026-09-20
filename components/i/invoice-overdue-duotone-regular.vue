<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e10hmz-ui"/><path class="w55fvi6vl"/><path class="nreq_9ofo"/><path class="csyuhrrop"/><path class="auud-gbvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:invoice-overdue-duotone-regular" /></template>
<style>
.auud-gbvk {
  d: path("M9.5 6.5h5l-5 5h5Z");
}

.csyuhrrop {
  d: path("M5 14V3h14v11");
}

.e10hmz-ui {
  fill: currentColor;
  d: path("M2 11v10h20V11L12 21Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nreq_9ofo {
  d: path("M2 11v10h20V11L12 21Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w55fvi6vl {
  fill: currentColor;
  d: path("M9.5 6.5h5l-5 5h5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
