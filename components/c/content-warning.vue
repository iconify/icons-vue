<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rzomey7hb"/><path class="sqah3_bcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:content-warning" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rzomey7hb {
  d: path("m14.285 6.793l5.251 9.29A2.625 2.625 0 0 1 17.251 20H6.749a2.625 2.625 0 0 1-2.285-3.917l5.251-9.29a2.625 2.625 0 0 1 4.57 0");
}

.sqah3_bcg {
  d: path("M8 14.5c2-3.5 6-3.5 8 0c-2 3.5-6 3.5-8 0m4 0h.01");
}

</style>
