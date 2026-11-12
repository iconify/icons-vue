<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><circle class="aqhok2bbj"/><path class="mxpc0lbwc"/><path class="xo0gn7bpl"/><path class="mho4m-bvk"/><path class="ynqplacsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:help-linear" /></template>
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

.mho4m-bvk {
  d: path("M9.17182 9.17157L4.92876 4.92822");
}

.mxpc0lbwc {
  d: path("M14.8281 9.17154L19.0722 4.92773");
}

.shu3xdl9q {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

.xo0gn7bpl {
  d: path("M4.92773 19.0723L9.17155 14.8286");
}

.ynqplacsi {
  d: path("M19.0723 19.0723L14.8284 14.8286");
}

</style>
