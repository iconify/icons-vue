<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jummnrbdg"/><path class="rf8p85b7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:convection-oven" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jummnrbdg {
  d: path("M7.375 3h9.25A4.375 4.375 0 0 1 21 7.375v9.25A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-9.25A4.375 4.375 0 0 1 7.375 3M3 7h18");
}

.rf8p85b7v {
  d: path("M12 14.5c-2.25-2-1.5-4.5 0-4.5s2.25 2.5 0 4.5m0 0c2.75-1 4.75 1 4 2.25s-3.5.75-4-2.25m0 0c-.5 3-3.25 3.5-4 2.25s1.25-3.25 4-2.25");
}

</style>
