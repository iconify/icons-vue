<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vd6tofbzt"/><path class="b47sztlwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:diner" /></template>
<style>
.b47sztlwa {
  d: path("M8.5 12.5h6V15a2.5 2.5 0 0 1-2.5 2.5h-1A2.5 2.5 0 0 1 8.5 15Zm6 .5h.5a1.75 1.75 0 0 1 0 3.5h-.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vd6tofbzt {
  d: path("m4.598 9.977l6.25-5.469a1.75 1.75 0 0 1 2.304 0l6.25 5.469A1.75 1.75 0 0 1 20 11.294v7.456a1.75 1.75 0 0 1-1.75 1.75H5.75A1.75 1.75 0 0 1 4 18.75v-7.456a1.75 1.75 0 0 1 .598-1.317M16 7V4h2v4.75");
}

</style>
