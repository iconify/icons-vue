<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e10hmz-ui"/><path class="nreq_9ofo"/><path class="csyuhrrop"/><path class="pty_wsbvs"/><path class="k0x593b0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:invoice-issue-duotone-regular" /></template>
<style>
.csyuhrrop {
  d: path("M5 14V3h14v11");
}

.e10hmz-ui {
  fill: currentColor;
  d: path("M2 11v10h20V11L12 21Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k0x593b0b {
  d: path("M13.5 6.5 16 9l-2.5 2.5");
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

.pty_wsbvs {
  d: path("M8 9h8");
}

</style>
