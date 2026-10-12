<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pb47rt7uh"/><circle class="bf9_qabtn"/><path class="rlb2dlbij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:invoice-stamp" /></template>
<style>
.bf9_qabtn {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pb47rt7uh {
  d: path("M6 2.75h7.5A2.25 2.25 0 0 1 15.75 5v6.24a6.5 6.5 0 0 0-3.56 10.01H6A2.25 2.25 0 0 1 3.75 19V5A2.25 2.25 0 0 1 6 2.75m1 4.5h5M7 10.5h5m-5 3.25h3");
}

.rlb2dlbij {
  d: path("m16 17.5l1.25 1.25l2.5-2.5");
}

</style>
