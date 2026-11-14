<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rikhm835w"/><path class="qmzdn0bpk"/><path class="a4dgxmbhp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lead-source-web" /></template>
<style>
.a4dgxmbhp {
  d: path("M10 9.75a2 4.75 0 1 0 4 0a2 4.75 0 1 0-4 0m-2.75 0h9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qmzdn0bpk {
  d: path("M7.25 9.75a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0");
}

.rikhm835w {
  d: path("M6.875 2h10.25A4.375 4.375 0 0 1 21.5 6.375v6.75a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 13.125v-6.75A4.375 4.375 0 0 1 6.875 2M12 17.5V21m-4 0h8");
}

</style>
