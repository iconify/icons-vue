<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="jl4903ezj"/><circle class="fbfyvgbuo"/><rect class="o_v_subpw"/><path class="nid46bcbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:creator-studio" /></template>
<style>
.fbfyvgbuo {
  cx: 12px;
  cy: 9.25px;
  r: 4.15px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jl4903ezj {
  cx: 12px;
  cy: 9.25px;
  r: 6.5px;
}

.nid46bcbk {
  d: path("M12 15.75v5.5m-4 0l4-2.75l4 2.75");
}

.o_v_subpw {
  width: 3px;
  height: 3px;
  x: 10.5px;
  y: 7.75px;
  rx: 1px;
}

</style>
