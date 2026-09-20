<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u7jotynzh"/><path class="mwsvi3abz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ash-cloud-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mwsvi3abz {
  d: path("m5 21 7 -7 7 7Z");
}

.u7jotynzh {
  d: path("M4 12a3.5 3.5 0 0 1 2 -6.5 4.5 4.5 0 0 1 8.5 -1A5 5 0 0 1 18 12Z");
}

</style>
