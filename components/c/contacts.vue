<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o_57trb_l"/><path class="s2poy7bhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contacts" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_57trb_l {
  d: path("M7 2.5h7.5A3.5 3.5 0 0 1 18 6v12a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18V6A3.5 3.5 0 0 1 7 2.5m11 4h2.5M18 12h2.5M18 17.5h2.5");
}

.s2poy7bhu {
  d: path("M8.25 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M7 17c0-2.25 1.7-3.5 3.75-3.5s3.75 1.25 3.75 3.5");
}

</style>
