<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xxg7_ht4u"/><path class="pfys7kw8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:damaru-drum" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pfys7kw8f {
  d: path("M17.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-6.5 0h-4m-3.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.xxg7_ht4u {
  d: path("M8.297 3.5h7.406a1.75 1.75 0 0 1 1.45 2.731l-3.24 4.788a1.75 1.75 0 0 0 0 1.962l3.24 4.788a1.75 1.75 0 0 1-1.45 2.731H8.297a1.75 1.75 0 0 1-1.45-2.731l3.24-4.788a1.75 1.75 0 0 0 0-1.962l-3.24-4.788A1.75 1.75 0 0 1 8.297 3.5M13.25 12h4");
}

</style>
