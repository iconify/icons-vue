<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bc40i0b_e"/><rect class="ipwiokbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chef-hat-star" /></template>
<style>
.bc40i0b_e {
  d: path("M7 13.75v-.5a3.5 3.5 0 0 1 1.5-6a3.6 3.6 0 0 1 7 0a3.5 3.5 0 0 1 1.5 6v.5Zm3 0v-2.5m4 2.5v-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipwiokbkl {
  width: 10px;
  height: 5px;
  x: 7px;
  y: 16.25px;
  rx: 1.5px;
}

</style>
