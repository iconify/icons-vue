<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wovvs0bhs"/><path class="beuio438u"/><path class="i31216-nv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:carpet-shop" /></template>
<style>
.beuio438u {
  d: path("M5.5 2.5h15a1.5 3 0 0 1 0 6m-15 0v10h15v-10m-15-3h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i31216-nv {
  d: path("m14.061 12.311l.128.128a1.5 1.5 0 0 1 0 2.122l-.128.128a1.5 1.5 0 0 1-2.122 0l-.128-.128a1.5 1.5 0 0 1 0-2.122l.128-.128a1.5 1.5 0 0 1 2.122 0M8.5 18.5V21m3-2.5V21m3-2.5V21m3-2.5V21");
}

.wovvs0bhs {
  d: path("M2.5 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
