<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x5v_oyatd"/><path class="m8mgcdbks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:angel-wings" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m8mgcdbks {
  d: path("M5 10.75q2 0 3.5-1.25m-1 4.75Q8.75 14 9.25 13M19 10.75q-2 0-3.5-1.25m1 4.75Q15.25 14 14.75 13");
}

.x5v_oyatd {
  d: path("M10.5 9.75C8.25 6.75 5.25 6 2.75 6.5c0 2.25.75 3.75 2.25 4.25c0 1.75 1 3 2.5 3.5c.25 1.5 1.25 2.75 3 3.25Zm3 0c2.25-3 5.25-3.75 7.75-3.25c0 2.25-.75 3.75-2.25 4.25c0 1.75-1 3-2.5 3.5c-.25 1.5-1.25 2.75-3 3.25Z");
}

</style>
