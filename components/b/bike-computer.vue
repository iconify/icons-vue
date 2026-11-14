<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zp2ex8zfi"/><path class="z4gy4_b5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-computer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z4gy4_b5n {
  d: path("M10.75 6h2.5A1.75 1.75 0 0 1 15 7.75v2.5A1.75 1.75 0 0 1 13.25 12h-2.5A1.75 1.75 0 0 1 9 10.25v-2.5A1.75 1.75 0 0 1 10.75 6M12 17v3.5m-9.5 0h19");
}

.zp2ex8zfi {
  d: path("M10.375 3h3.25A4.375 4.375 0 0 1 18 7.375v5.25A4.375 4.375 0 0 1 13.625 17h-3.25A4.375 4.375 0 0 1 6 12.625v-5.25A4.375 4.375 0 0 1 10.375 3");
}

</style>
