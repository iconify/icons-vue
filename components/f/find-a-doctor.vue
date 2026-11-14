<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r470zbg-b"/><path class="uobyqtxnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:find-a-doctor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r470zbg-b {
  d: path("M12 21.5S4.5 15 4.5 9.5a7.5 7.5 0 0 1 15 0c0 5.5-7.5 12-7.5 12");
}

.uobyqtxnu {
  d: path("M9.25 5.5v2.25c0 1.5 1 2.5 2.25 2.5s2.25-1 2.25-2.5V5.5m-2.25 4.75V11c0 1 .75 1.75 1.75 1.75S15 12 15 11.25M14 10a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
