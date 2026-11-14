<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dwm2vpb0y"/><path class="spdsprmxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bank-closed" /></template>
<style>
.dwm2vpb0y {
  d: path("M4 2.5h16A1.5 1.5 0 0 1 21.5 4A1.5 1.5 0 0 1 20 5.5H4A1.5 1.5 0 0 1 2.5 4A1.5 1.5 0 0 1 4 2.5m0 3V15h16V5.5M4 8.25h16M4 11h16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.spdsprmxc {
  d: path("M10.5 18.5v-3a1.5 1.5 0 0 1 3 0v3m-2.5 0h2a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 13 22h-2a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 11 18.5");
}

</style>
