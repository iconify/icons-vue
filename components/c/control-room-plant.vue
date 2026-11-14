<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h9wwflqkn"/><path class="j0kecjf9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:control-room-plant" /></template>
<style>
.h9wwflqkn {
  d: path("M4 3h5a1.5 1.5 0 0 1 1.5 1.5v6A1.5 1.5 0 0 1 9 12H4a1.5 1.5 0 0 1-1.5-1.5v-6A1.5 1.5 0 0 1 4 3m11 0h5a1.5 1.5 0 0 1 1.5 1.5v6A1.5 1.5 0 0 1 20 12h-5a1.5 1.5 0 0 1-1.5-1.5v-6A1.5 1.5 0 0 1 15 3M2.5 16.5h19m-17 0V21m15-4.5V21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j0kecjf9u {
  d: path("M2.5 12a4 4 0 0 1 8 0m-4 0l2-3m8 3V8.5M19 12V6.5");
}

</style>
