<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s2lfktbpm"/><path class="k3vcnrb_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:game-dev" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k3vcnrb_m {
  d: path("M10 7L7.5 9.5L10 12m4-5l2.5 2.5L14 12");
}

.s2lfktbpm {
  d: path("M7.125 4h9.75A2.625 2.625 0 0 1 19.5 6.625v5.75A2.625 2.625 0 0 1 16.875 15h-9.75A2.625 2.625 0 0 1 4.5 12.375v-5.75A2.625 2.625 0 0 1 7.125 4M4.5 15l-2 4h19l-2-4");
}

</style>
