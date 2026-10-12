<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="oii_ckbex"/><path class="ruy21gbpd"/><circle class="lgl_seb5t"/><path class="qsd0rsxse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:internet-radio" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lgl_seb5t {
  cx: 16.25px;
  cy: 14.25px;
  r: 2.5px;
}

.oii_ckbex {
  width: 18.5px;
  height: 12px;
  x: 2.75px;
  y: 8.25px;
  rx: 2.5px;
}

.qsd0rsxse {
  d: path("M6.25 12.5h4.5M6.25 16h4.5");
}

.ruy21gbpd {
  d: path("M7.5 8.25L12.75 3");
}

</style>
