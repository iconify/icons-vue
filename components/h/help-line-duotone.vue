<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tof57eb9e"/><circle class="shu3xdl9q"/><circle class="aqhok2bbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:help-line-duotone" /></template>
<style>
.aqhok2bbj {
  cx: 12px;
  cy: 12px;
  r: 4px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.shu3xdl9q {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

.tof57eb9e {
  d: path("M14.8284 9.17154L19.0724 4.92773M4.92773 19.0723L9.17155 14.8286M9.17157 9.17157L4.92851 4.92822M19.0723 19.0723L14.8284 14.8286");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
