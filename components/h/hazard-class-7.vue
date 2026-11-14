<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="llayhcb1x"/><path class="u67nmbc_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hazard-class-7" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.llayhcb1x {
  d: path("m13.856 3.856l6.288 6.288a2.625 2.625 0 0 1 0 3.712l-6.288 6.288a2.625 2.625 0 0 1-3.712 0l-6.288-6.288a2.625 2.625 0 0 1 0-3.712l6.288-6.288a2.625 2.625 0 0 1 3.712 0");
}

.u67nmbc_s {
  d: path("m13 13.75l1.5 2.5a5 5 0 0 1-5 0l1.5-2.5a2 2 0 0 0 2 0M10 12H7a5 5 0 0 1 2.5-4.25l1.5 2.5A2 2 0 0 0 10 12m3-1.75l1.5-2.5A5 5 0 0 1 17 12h-3a2 2 0 0 0-1-1.75M12 12h.01");
}

</style>
