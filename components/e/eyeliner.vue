<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="srzo4dbvh"/><circle class="ivjch5bsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eyeliner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ivjch5bsa {
  cx: 10.15px;
  cy: 14px;
  r: 2.25px;
}

.srzo4dbvh {
  d: path("M2.75 14c2.2 3.2 4.9 4.75 7.4 4.75s5.2-1.55 7.35-4.75M2.75 14c2.2-3.2 4.9-4.75 7.4-4.75s5.2 1.55 7.35 4.75l3.75-3.75");
}

</style>
