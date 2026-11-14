<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d05mc8dhn"/><path class="gun6-2b9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heating-outage" /></template>
<style>
.d05mc8dhn {
  d: path("m4 10.5l8-7l8 7v9a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2ZM3 3l5.798 5.798m9.758 9.758L21 21m0-18l-4.95 4.95M5.514 18.486L3 21");
}

.gun6-2b9f {
  d: path("M8.5 18.5h7c1.5-2.5.5-6-2.5-10c0 3-1.5 4-2.5 2.5c-2.5 2.5-3 5.5-2 7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
