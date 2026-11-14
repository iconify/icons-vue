<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qs64qgbaq"/><path class="k8nu7-t-v"/><path class="gyr1xkbea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kiln-open" /></template>
<style>
.gyr1xkbea {
  d: path("M10 18.5c-1.5 0-1.75-1.75 0-3.5c1.75 1.75 1.5 3.5 0 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k8nu7-t-v {
  d: path("M8.5 4.25V2.5h3v1.75m6 8.75l3-2v9.5l-3 1m-12 0V14a4.5 4.5 0 0 1 9 0v7.5");
}

.qs64qgbaq {
  d: path("M2.5 21.5V11a7.5 7.5 0 0 1 15 0v10.5Z");
}

</style>
