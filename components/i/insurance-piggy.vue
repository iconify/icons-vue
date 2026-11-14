<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jf7_7qb1y"/><path class="r2iqt9bej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:insurance-piggy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jf7_7qb1y {
  d: path("M4 11.5c0-3.5 3.6-6 8-6s8 2.5 8 6c0 2.2-1.3 4-3.5 5V19H14v-1.75c-.65.15-1.3.25-2 .25s-1.35-.1-2-.25V19H7.5v-2.5c-2.2-1-3.5-2.8-3.5-5");
}

.r2iqt9bej {
  d: path("M4.5 10h-2v3h2m3.25-2.75h.01m5.49-1.5l2.5 1v1.5c0 1.4-1.1 2.25-2.5 2.75c-1.4-.5-2.5-1.35-2.5-2.75v-1.5Z");
}

</style>
