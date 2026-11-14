<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sd78bdv7m"/><path class="jec5cf1if"/><path class="xqqyh46ln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:database-replica" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jec5cf1if {
  d: path("M8.5 12v7a6 2.5 0 0 0 12 0v-7M3 4.5a6 2.25 0 1 0 12 0a6 2.25 0 1 0-12 0");
}

.sd78bdv7m {
  d: path("M8.5 12a6 2.5 0 1 0 12 0a6 2.5 0 1 0-12 0");
}

.xqqyh46ln {
  d: path("M3 4.5v8a6 2.25 0 0 0 2.5 1.75");
}

</style>
