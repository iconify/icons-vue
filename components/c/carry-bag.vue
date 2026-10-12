<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uuqxg7dkq"/><rect class="jqgfwpbsz"/><path class="c74hquiwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:carry-bag" /></template>
<style>
.c74hquiwb {
  d: path("M5.75 13.5h12.5m-9.5 5.75v2m6.5-2v2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jqgfwpbsz {
  width: 12.5px;
  height: 10.5px;
  x: 5.75px;
  y: 8.75px;
  rx: 2.25px;
}

.uuqxg7dkq {
  d: path("M9.75 8.75v-5a1 1 0 0 1 1-1h2.5a1 1 0 0 1 1 1v5");
}

</style>
