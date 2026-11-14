<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s5el-eb7f"/><path class="t2d3u0b9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cool-roof" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s5el-eb7f {
  d: path("m4.611 12.716l5.875-4.147a2.625 2.625 0 0 1 3.028 0l5.875 4.147A2.63 2.63 0 0 1 20.5 14.86v4.015a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 18.875V14.86a2.63 2.63 0 0 1 1.111-2.144");
}

.t2d3u0b9h {
  d: path("M10 21.5v-4h4v4M6.5 8L4.25 5M12 4.75V2.5M17.5 8l2.25-3");
}

</style>
