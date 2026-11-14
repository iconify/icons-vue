<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vtzcmxbfa"/><path class="p-yrlt54u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boiler" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p-yrlt54u {
  d: path("M12 15c-1.75 0-2.75-1.25-2.75-2.75C9.25 10.5 10.75 9.5 11 8c1 .75 1.5 1.5 1.5 2.5c.5-.5.75-1 1-1.75c.75 1 1.25 2.25 1.25 3.5c0 1.5-1 2.75-2.75 2.75m-3 2.5v4m6-4v4");
}

.vtzcmxbfa {
  d: path("M8.5 2.5h7A3.5 3.5 0 0 1 19 6v8a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 14V6a3.5 3.5 0 0 1 3.5-3.5m.5 3h6");
}

</style>
