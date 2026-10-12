<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w8c3zdb-s"/><path class="oc_ndnbfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cracked-tooth" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oc_ndnbfa {
  d: path("m12 4.25l-1.75 3.5l2.5 2.25l-1.5 3");
}

.w8c3zdb-s {
  d: path("M7.5 3.25c-2.6 0-4.25 2.1-4.25 4.75c0 2.4 1 4 1.75 6.25c.7 2.1.9 7 3 7c1.9 0 1.6-5.25 4-5.25s2.1 5.25 4 5.25c2.1 0 2.3-4.9 3-7C19.75 12 20.75 10.4 20.75 8c0-2.65-1.65-4.75-4.25-4.75c-1.9 0-2.7 1-4.5 1s-2.6-1-4.5-1");
}

</style>
