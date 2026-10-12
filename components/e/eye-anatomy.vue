<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j44yygbko"/><circle class="w6ucblb_v"/><path class="e_mqbzbed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eye-anatomy" /></template>
<style>
.e_mqbzbed {
  d: path("M19.5 12h1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j44yygbko {
  d: path("M6.44 8.5a7 7 0 1 1 0 7c-2.19-1-2.19-6 0-7");
}

.w6ucblb_v {
  cx: 9.5px;
  cy: 12px;
  r: 1.5px;
}

</style>
