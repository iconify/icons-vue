<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h_jnrccyg"/><path class="cb_kavbxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:apple" /></template>
<style>
.cb_kavbxs {
  d: path("M12 8.5c0-2.5 1-4.5 3-5");
}

.h_jnrccyg {
  d: path("M12 8.5c-2.5-2-6.5-.5-6.5 4C5.5 16.75 8 20 10 20c1 0 1.5-.5 2-.5s1 .5 2 .5c2 0 4.5-3.25 4.5-7.5c0-4.5-4-6-6.5-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
