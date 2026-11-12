<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kfrug7s3s"/><path class="uyjuokbvi"/><path class="vtwk979ug"/><path class="xggl6t9lq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevrons-down-up-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfrug7s3s {
  d: path("M18 21L12 15L6 21");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.uyjuokbvi {
  d: path("M9 18L12 15L18 21");
}

.vtwk979ug {
  d: path("M18 3L12 9L6 3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xggl6t9lq {
  d: path("M9 6L12 9L18 3");
}

</style>
