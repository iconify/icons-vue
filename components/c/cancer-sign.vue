<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ulfr24xqb"/><path class="kagbwcbhh"/><circle class="usz72eb9x"/><path class="gcgmiybrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cancer-sign" /></template>
<style>
.gcgmiybrc {
  d: path("M17.25 18c-3.5 2.5-9.25 2.5-13.5-.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kagbwcbhh {
  d: path("M6.75 6c3.5-2.5 9.25-2.5 13.5.5");
}

.ulfr24xqb {
  cx: 6.75px;
  cy: 8.75px;
  r: 2.75px;
}

.usz72eb9x {
  cx: 17.25px;
  cy: 15.25px;
  r: 2.75px;
}

</style>
