<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jz9wy2bsc"/><path class="xtxc_b2sh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-transfer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jz9wy2bsc {
  d: path("M13.75 2.75h-6.5a2.5 2.5 0 0 0-2.5 2.5v13.5a2.5 2.5 0 0 0 2.5 2.5h9.5a2.5 2.5 0 0 0 2.5-2.5V8.25Z");
}

.xtxc_b2sh {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-10.75 4h6.75m-2-1.75l2 1.75l-2 1.75m2.25 2.5H8.75m2-1.75l-2 1.75l2 1.75");
}

</style>
