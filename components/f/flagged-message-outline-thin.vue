<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hbdbg_bcy"/><path class="lyjarcbwz"/><path class="m9ofx6bgv"/><path class="zmudarbqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flagged-message-outline-thin" /></template>
<style>
.hbdbg_bcy {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lyjarcbwz {
  d: path("M7 18v3l3 -3");
}

.m9ofx6bgv {
  d: path("M8 6v9");
}

.zmudarbqd {
  d: path("M8 6h7l-2 2 2 2H8");
}

</style>
