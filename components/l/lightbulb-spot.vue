<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q_z1wmbbn"/><path class="zzry5-bop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lightbulb-spot" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q_z1wmbbn {
  d: path("M10.5 11.5V9.25a3.5 3.5 0 1 1 3 0v2.25");
}

.zzry5-bop {
  d: path("M9.389 11.5h5.222a1.75 1.75 0 0 1 1.128.411l1.886 1.589a1.133 1.133 0 0 1-.73 2h-9.79a1.133 1.133 0 0 1-.73-2l1.886-1.589a1.75 1.75 0 0 1 1.128-.411M6.5 18.25L5 21.5m7-3.25v3.25m5.5-3.25L19 21.5");
}

</style>
