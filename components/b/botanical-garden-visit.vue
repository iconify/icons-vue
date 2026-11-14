<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tcyl4zb-m"/><path class="orvdlwbaa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:botanical-garden-visit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.orvdlwbaa {
  d: path("M12 16c-3.5 0-4.5-3-4.5-5.5c3 0 4.5 2.5 4.5 5.5m0-2.5c0-3.25 1.25-5.5 4-5.5c0 2.75-1.25 5.5-4 5.5m0 0V21");
}

.tcyl4zb-m {
  d: path("M3 21v-9a9 9 0 0 1 18 0v9Z");
}

</style>
