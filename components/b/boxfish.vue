<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="chbb0obbn"/><path class="yzpfjib8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boxfish" /></template>
<style>
.chbb0obbn {
  d: path("M6.5 7.75H12a3.5 3.5 0 0 1 3.5 3.5v4a3.5 3.5 0 0 1-3.5 3.5H6.5a3.5 3.5 0 0 1-3.5-3.5v-4a3.5 3.5 0 0 1 3.5-3.5m9 4.5l2.5 1l3-3.5q-1 3.5 0 7l-3-3.5l-2.5 1m-8-6.5l2-2.5l2 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yzpfjib8q {
  d: path("m9 14l2.5-1.5v3Zm-2.5-2.75h.01");
}

</style>
