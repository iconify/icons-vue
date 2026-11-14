<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="njy2gabgk"/><path class="s8_z00p_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delete-restore" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.njy2gabgk {
  d: path("M8.319 6.5h7.362a2.625 2.625 0 0 1 2.618 2.812l-.625 8.75a2.625 2.625 0 0 1-2.618 2.438H8.944a2.625 2.625 0 0 1-2.618-2.438l-.625-8.75A2.625 2.625 0 0 1 8.319 6.5M3.5 6.5h17M9 6.5v-2c0-.55.45-1 1-1h4c.55 0 1 .45 1 1v2m-3 11V11");
}

.s8_z00p_g {
  d: path("M9.5 13.5L12 11l2.5 2.5");
}

</style>
