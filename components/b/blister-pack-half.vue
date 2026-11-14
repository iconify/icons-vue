<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yr9h8rbjd"/><path class="gthi3mj1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blister-pack-half" /></template>
<style>
.gthi3mj1v {
  d: path("M4.25 9.5V14a1.25 1.25 0 0 0 2.5 0V9.5m1.75 0V14a1.25 1.25 0 0 0 2.5 0V9.5m3.25-.5za1.25 1.25 0 0 1 1.25 1.25v3.5A1.25 1.25 0 0 1 14.25 15A1.25 1.25 0 0 1 13 13.75v-3.5A1.25 1.25 0 0 1 14.25 9m4.25 0za1.25 1.25 0 0 1 1.25 1.25v3.5A1.25 1.25 0 0 1 18.5 15a1.25 1.25 0 0 1-1.25-1.25v-3.5A1.25 1.25 0 0 1 18.5 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yr9h8rbjd {
  d: path("M6 6.5h12a3.5 3.5 0 0 1 3.5 3.5v4a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 14v-4A3.5 3.5 0 0 1 6 6.5");
}

</style>
