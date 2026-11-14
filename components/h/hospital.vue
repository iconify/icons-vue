<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lawlvp_ig"/><path class="sq-0v8bvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hospital" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lawlvp_ig {
  d: path("M8 4.5h8A3.5 3.5 0 0 1 19.5 8v9.5A3.5 3.5 0 0 1 16 21H8a3.5 3.5 0 0 1-3.5-3.5V8A3.5 3.5 0 0 1 8 4.5M2.5 21h19M12 8.5v5M9.5 11h5");
}

.sq-0v8bvq {
  d: path("M10.5 21v-3.5h3V21");
}

</style>
