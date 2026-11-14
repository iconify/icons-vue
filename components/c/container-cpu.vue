<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tc3id9jmw"/><path class="hh06y952p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:container-cpu" /></template>
<style>
.hh06y952p {
  d: path("M10.375 7.75h3.25a2.625 2.625 0 0 1 2.625 2.625v3.25a2.625 2.625 0 0 1-2.625 2.625h-3.25a2.625 2.625 0 0 1-2.625-2.625v-3.25a2.625 2.625 0 0 1 2.625-2.625m.125 0v-2.5m3 2.5v-2.5m-3 11v2.5m3-2.5v2.5M7.75 10.5h-2.5m2.5 3h-2.5m11-3h2.5m-2.5 3h2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tc3id9jmw {
  d: path("M8.625 2.5h6.75A6.125 6.125 0 0 1 21.5 8.625v6.75a6.125 6.125 0 0 1-6.125 6.125h-6.75A6.125 6.125 0 0 1 2.5 15.375v-6.75A6.125 6.125 0 0 1 8.625 2.5");
}

</style>
