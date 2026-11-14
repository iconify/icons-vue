<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="naiqnjb-b"/><path class="drojoniiz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:free-kick" /></template>
<style>
.drojoniiz {
  d: path("M16.75 7L19 9.25L21.25 7M9.332 13.805l.405.27a1.5 1.5 0 0 1 .561 1.805l-.171.427a1.5 1.5 0 0 1-1.393.943h-.468a1.5 1.5 0 0 1-1.393-.943l-.171-.427a1.5 1.5 0 0 1 .561-1.805l.405-.27a1.5 1.5 0 0 1 1.664 0M8.5 13.25V9.5m2.25 5.25l3.5-1m-4.5 3.5l2.25 3m-4.75-3l-2.25 3m1.25-5.5l-3.5-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.naiqnjb-b {
  d: path("M2.5 15.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0m6-8.75c0-2.5 2.5-4 5.25-4c3 0 5.25 1.75 5.25 6.5");
}

</style>
