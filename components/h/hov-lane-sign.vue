<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="llayhcb1x"/><path class="qcbxp-bfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hov-lane-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.llayhcb1x {
  d: path("m13.856 3.856l6.288 6.288a2.625 2.625 0 0 1 0 3.712l-6.288 6.288a2.625 2.625 0 0 1-3.712 0l-6.288-6.288a2.625 2.625 0 0 1 0-3.712l6.288-6.288a2.625 2.625 0 0 1 3.712 0");
}

.qcbxp-bfq {
  d: path("M7.5 13.5V12l2.25-3h4.5l2.25 3v1.5h-1a1.5 1.5 0 0 0-3 0h-1a1.5 1.5 0 0 0-3 0Z");
}

</style>
