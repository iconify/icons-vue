<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nb6fasbvt"/><path class="l02t2qs1j"/><path class="vypfsppjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:concurrency" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l02t2qs1j {
  d: path("M19.5 3.5L21 6l-2.75 1M3 18q8-7 16-4");
}

.nb6fasbvt {
  d: path("M5 10q8-7 16-4");
}

.vypfsppjx {
  d: path("M17.5 11.5L19 14l-2.75 1");
}

</style>
