<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d5a07ccog"/><path class="tbkj4c70g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loop-trail" /></template>
<style>
.d5a07ccog {
  d: path("M21 10a9.5 6.5 0 0 1 0 4m-2 2.25a9.5 6.5 0 0 1-5 2m-4 0a9.5 6.5 0 0 1-5-2M3 14a9.5 6.5 0 0 1 0-4m2-2.25a9.5 6.5 0 0 1 5-2m4 0a9.5 6.5 0 0 1 5 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tbkj4c70g {
  d: path("m18.5 4.75l.5 3l-3 .5");
}

</style>
