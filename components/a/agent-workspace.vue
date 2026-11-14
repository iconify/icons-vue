<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vjhci854a"/><path class="lcrbz137h"/><path class="ciid5bzeo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:agent-workspace" /></template>
<style>
.ciid5bzeo {
  d: path("M8.5 9.5v-.75a3.5 3.5 0 0 1 7 0v.75m-7.5 7c0-1.9 1.8-3.25 4-3.25s4 1.35 4 3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lcrbz137h {
  d: path("M10.25 8.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.vjhci854a {
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5V13a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 13V6.5A3.5 3.5 0 0 1 6 3m6 13.5v4m-3.5 0h7");
}

</style>
