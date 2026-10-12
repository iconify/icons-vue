<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rxe_0qbze"/><rect class="a9-9w__6c"/><path class="rw3lygzul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:boom-barrier" /></template>
<style>
.a9-9w__6c {
  width: 14px;
  height: 3.75px;
  x: 7.25px;
  y: 8.5px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rw3lygzul {
  d: path("m11.5 8.5l-1.75 3.75M15.5 8.5l-1.75 3.75M19.5 8.5l-1.75 3.75");
}

.rxe_0qbze {
  width: 4.5px;
  height: 14.75px;
  x: 2.75px;
  y: 6.5px;
  rx: 1.25px;
}

</style>
