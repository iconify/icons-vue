<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="goo_0kboz"/><path class="lqsvcdcna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aisle-sign" /></template>
<style>
.goo_0kboz {
  d: path("M4.75 9h14.5A1.75 1.75 0 0 1 21 10.75v7.5A1.75 1.75 0 0 1 19.25 20H4.75A1.75 1.75 0 0 1 3 18.25v-7.5A1.75 1.75 0 0 1 4.75 9M2.5 3.5h19M7 3.5V9m10-5.5V9M6.5 14.5h11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lqsvcdcna {
  d: path("m14.5 11.75l3 2.75l-3 2.75");
}

</style>
