<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ri1q1abce"/><path class="tcgbbxbli"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:circuit-breaker" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ri1q1abce {
  d: path("M7.875 2.5h8.25A4.375 4.375 0 0 1 20.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-8.25A4.375 4.375 0 0 1 3.5 17.125V6.875A4.375 4.375 0 0 1 7.875 2.5M12 6.5V12");
}

.tcgbbxbli {
  d: path("M11.875 12h.25a2.625 2.625 0 0 1 2.625 2.625v.75A2.625 2.625 0 0 1 12.125 18h-.25a2.625 2.625 0 0 1-2.625-2.625v-.75A2.625 2.625 0 0 1 11.875 12");
}

</style>
