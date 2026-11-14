<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t14_i3m5x"/><path class="k2mdc2baa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:expense" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2mdc2baa {
  d: path("M14.25 9.5C14 8.65 13.15 8.25 12 8.25c-1.4 0-2.25.7-2.25 1.75c0 2.1 4.5 1.2 4.5 4c0 1-.95 1.75-2.25 1.75c-1.2 0-2.05-.5-2.25-1.25M12 6.75v1.5m0 7.5v1.5");
}

.t14_i3m5x {
  d: path("M6.75 3h10.5A1.75 1.75 0 0 1 19 4.75v14.234A1.17 1.17 0 0 1 17.25 20l-.882-.504a1.75 1.75 0 0 0-1.736 0l-1.764 1.008a1.75 1.75 0 0 1-1.736 0l-1.764-1.008a1.75 1.75 0 0 0-1.736 0L6.75 20A1.17 1.17 0 0 1 5 18.984V4.75A1.75 1.75 0 0 1 6.75 3");
}

</style>
