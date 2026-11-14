<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vyxjj9b7c"/><path class="aaizh6pml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:consent-form" /></template>
<style>
.aaizh6pml {
  d: path("M7.5 17.5c1-2.5 2.25-2.5 2.5-.25c.25 1.75 1.5 1.5 2-.5c.5-1.25 1.5-.75 1.75.5h2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vyxjj9b7c {
  d: path("M8 2.5h8A3.5 3.5 0 0 1 19.5 6v12a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18V6A3.5 3.5 0 0 1 8 2.5m0 4h8M8 10h8");
}

</style>
