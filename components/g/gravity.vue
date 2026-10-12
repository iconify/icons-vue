<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="c5p5-digf"/><path class="rjn0mgvml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gravity" /></template>
<style>
.c5p5-digf {
  cx: 12px;
  cy: 7px;
  r: 4.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rjn0mgvml {
  d: path("M12 13.25v5.25m-2.75-2.75L12 18.5l2.75-2.75m-10 5.5h14.5");
}

</style>
