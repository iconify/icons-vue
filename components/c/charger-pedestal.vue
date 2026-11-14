<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ymdnp41yi"/><path class="mepfaph9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charger-pedestal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mepfaph9d {
  d: path("M10.5 6.5L8 11h3l-2.5 4.5");
}

.ymdnp41yi {
  d: path("M8.5 2.5h2A3.5 3.5 0 0 1 14 6v12a3.5 3.5 0 0 1-3.5 3.5h-2A3.5 3.5 0 0 1 5 18V6a3.5 3.5 0 0 1 3.5-3.5M14 17c3 0 5-1.5 5-5V7");
}

</style>
