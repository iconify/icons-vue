<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yqbzscbua"/><path class="j6xzs2bsb"/><path class="xnjrtbc3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:agar-plate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6xzs2bsb {
  d: path("M2.5 9.5v4a9.5 5.5 0 0 0 19 0v-4");
}

.xnjrtbc3s {
  d: path("M5 10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.5-2a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.5 2a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.yqbzscbua {
  d: path("M2.5 9.5a9.5 5.5 0 1 0 19 0a9.5 5.5 0 1 0-19 0");
}

</style>
