<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q9oz5kb8k"/><path class="xj0-uvb6m"/><path class="ps0r8ibbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hair-braid" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ps0r8ibbh {
  d: path("m9.319 13.177l3.172-1.479a2 2 0 0 1 2.658.967a2 2 0 0 1-.968 2.658l-3.172 1.479a2 2 0 0 1-2.658-.967a2 2 0 0 1 .968-2.658M10.25 19h3.5M12 19l-1.25 2.5M12 19l1.25 2.5");
}

.q9oz5kb8k {
  d: path("m9.319 4.677l3.172-1.479a2 2 0 0 1 2.658.967a2 2 0 0 1-.968 2.658l-3.172 1.479a2 2 0 0 1-2.658-.967a2 2 0 0 1 .968-2.658");
}

.xj0-uvb6m {
  d: path("m11.509 7.448l3.172 1.479a2 2 0 0 1 .968 2.658a2 2 0 0 1-2.658.967l-3.172-1.479a2 2 0 0 1-.968-2.658a2 2 0 0 1 2.658-.967");
}

</style>
