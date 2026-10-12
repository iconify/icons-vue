<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l82dqub3m"/><path class="onn2neelc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hourglass" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l82dqub3m {
  d: path("M7.25 2.75v2.5c0 2.6 1.6 4.5 4.75 6.75c-3.15 2.25-4.75 4.15-4.75 6.75v2.5h9.5v-2.5c0-2.6-1.6-4.5-4.75-6.75c3.15-2.25 4.75-4.15 4.75-6.75v-2.5Zm-1.5 0h12.5m-12.5 18.5h12.5");
}

.onn2neelc {
  d: path("M9.75 18.75c.3-1.25 1-2 2.25-2.75c1.25.75 1.95 1.5 2.25 2.75Z");
}

</style>
