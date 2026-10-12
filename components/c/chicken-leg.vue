<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n-1ei338t"/><circle class="mq6912bci"/><circle class="pklpjen4v"/><path class="qh0o9vbpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chicken-leg" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mq6912bci {
  cx: 4.75px;
  cy: 17.25px;
  r: 1.5px;
}

.n-1ei338t {
  d: path("M9 15.25c-.75-1.75-1.25-3.75-1.25-6a6.25 6.25 0 0 1 12.5 0c0 3.5-2.75 6.25-6.25 6.25c-1.75 0-3.25-.25-5-.25m0 0L6.25 18");
}

.pklpjen4v {
  cx: 6.75px;
  cy: 19.25px;
  r: 1.5px;
}

.qh0o9vbpz {
  d: path("M11.25 8.5A2.75 2.75 0 0 1 14 5.75");
}

</style>
