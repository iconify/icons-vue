<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rdxjhmbhz"/><path class="qdxck2k7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:courier-handheld" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qdxck2k7s {
  d: path("M14 6h2.5A1.5 1.5 0 0 1 18 7.5A1.5 1.5 0 0 1 16.5 9H14a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 14 6m-4.5 6l-1 3.5");
}

.rdxjhmbhz {
  d: path("M2.5 3h16A2.5 2.5 0 0 1 21 5.5v4a2.5 2.5 0 0 1-2.5 2.5H16l1.5 7.5a1.5 1.5 0 0 1-1.5 2h-2.5a1.5 1.5 0 0 1-1.5-1.25L10.5 12l-8-2.5Z");
}

</style>
