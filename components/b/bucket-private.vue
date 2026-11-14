<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ehv5k_5zm"/><path class="wzg9f9-5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bucket-private" /></template>
<style>
.ehv5k_5zm {
  d: path("M3 4h18l-1.5 13.5A2.5 2.5 0 0 1 17 20H7a2.5 2.5 0 0 1-2.5-2.5Zm.5 3.75h17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wzg9f9-5k {
  d: path("M11 13h2a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 13 17h-2a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 11 13m-.5 0v-.5a1.5 1.5 0 0 1 3 0v.5");
}

</style>
