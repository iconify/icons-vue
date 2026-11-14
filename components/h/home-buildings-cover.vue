<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pv6e66f2v"/><path class="z91gwbcsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-buildings-cover" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pv6e66f2v {
  d: path("m4.53 8.212l5.875-4.493a2.625 2.625 0 0 1 3.19 0l5.875 4.493a2.63 2.63 0 0 1 1.03 2.085v8.578a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 18.875v-8.578a2.63 2.63 0 0 1 1.03-2.085");
}

.z91gwbcsz {
  d: path("M11.5 10h1a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 10 12v-.5a1.5 1.5 0 0 1 1.5-1.5m-1.25 11.5v-3.25a1.75 1.75 0 0 1 3.5 0v3.25");
}

</style>
