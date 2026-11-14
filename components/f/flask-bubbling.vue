<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oombvifuw"/><path class="swwndvdgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flask-bubbling" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oombvifuw {
  d: path("M8 2.5h8m-6.5 0V8a7 7 0 1 0 5 0V2.5M6 11h12");
}

.swwndvdgz {
  d: path("M8.25 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5-2a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
