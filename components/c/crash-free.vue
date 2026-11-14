<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ccb46tbsv"/><path class="dkvdnlczs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crash-free" /></template>
<style>
.ccb46tbsv {
  d: path("m12 2.5l7.5 2.75V11c0 4.5-3 8-7.5 10.5c-4.5-2.5-7.5-6-7.5-10.5V5.25Z");
}

.dkvdnlczs {
  d: path("m8.5 11.75l2.5 2.5l4.75-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
