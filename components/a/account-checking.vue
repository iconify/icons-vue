<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p_6dgwbil"/><path class="a1npssi8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-checking" /></template>
<style>
.a1npssi8d {
  d: path("M9.75 9.25C10.5 8 11 8 11.25 8.75s.75.75 1.5-.25m8.25 5h-3.5a2.25 2.25 0 0 0 0 4.5H21m-3-2.25h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p_6dgwbil {
  d: path("M7.375 11h9.25A4.375 4.375 0 0 1 21 15.375v1.75a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 17.125v-1.75A4.375 4.375 0 0 1 7.375 11M6.5 11l2.25-8.25l7.75 2L14.75 11M10 6l4.5 1.25");
}

</style>
