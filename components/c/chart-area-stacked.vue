<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ux32n0bfz"/><path class="a0og-zbih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-area-stacked" /></template>
<style>
.a0og-zbih {
  d: path("M7.25 15.75v-2q0-1 .66-1.75l2.43-2.75q.66-.75 1.42-.1l1.73 1.45q.76.65 1.47-.06l4.08-4.08q.71-.71.71.29v9q0 1-1 1H8.25q-1 0-1-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux32n0bfz {
  d: path("M3.75 3.75v14.5a2 2 0 0 0 2 2h14.5");
}

</style>
