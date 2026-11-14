<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w-jalus4w"/><path class="euo_qvrde"/><path class="y0mft7lsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lily-pond" /></template>
<style>
.euo_qvrde {
  d: path("M12 12.5c-3-1-6-2-7.5-4c3-.5 6 1 7.5 4m0 0c3-1 6-2 7.5-4c-3-.5-6 1-7.5 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w-jalus4w {
  d: path("M12 3.5c2.5 2 2.5 7 0 9c-2.5-2-2.5-7 0-9");
}

.y0mft7lsg {
  d: path("M4.5 14.5a7.5 2 0 1 0 15 0a7.5 2 0 1 0-15 0M3 20q2.25-1 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
