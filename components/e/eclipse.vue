<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o1z2wccdo"/><path class="p29821bzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eclipse" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o1z2wccdo {
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.p29821bzi {
  d: path("M16.442 14.244a5 5 0 0 1-6.686-6.686M12 2.5v2m0 15v2M2.5 12h2m15 0h2M5.25 5.25l1.5 1.5m10.5 10.5l1.5 1.5m0-13.5l-1.5 1.5m-12 12l1.5-1.5");
}

</style>
