<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="awyoa7tdg"/><path class="x5vf23s9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gift-box-shipping" /></template>
<style>
.awyoa7tdg {
  d: path("M6.625 10h10.75A2.625 2.625 0 0 1 20 12.625v4.75A2.625 2.625 0 0 1 17.375 20H6.625A2.625 2.625 0 0 1 4 17.375v-4.75A2.625 2.625 0 0 1 6.625 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x5vf23s9p {
  d: path("M4.75 7h14.5A1.75 1.75 0 0 1 21 8.75a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 8.75A1.75 1.75 0 0 1 4.75 7M12 7v13m0-13c-2-3.5-5-3.5-4-1c.5 1 2 1 4 1m0 0c2-3.5 5-3.5 4-1c-.5 1-2 1-4 1");
}

</style>
