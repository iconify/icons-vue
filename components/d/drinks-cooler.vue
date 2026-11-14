<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k7k4m147z"/><path class="p8a8swx0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drinks-cooler" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k7k4m147z {
  d: path("M6.125 2.5h11.75A2.625 2.625 0 0 1 20.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 18.875V5.125A2.625 2.625 0 0 1 6.125 2.5M3.5 6h17m-17 7.5h13M3.5 20h13");
}

.p8a8swx0j {
  d: path("M6 13.5V11c0-.75.75-1.25.75-1.75V8h1.5v1.25c0 .5.75 1 .75 1.75v2.5m2 0V11c0-.75.75-1.25.75-1.75V8h1.5v1.25c0 .5.75 1 .75 1.75v2.5M6 20v-2.5c0-.75.75-1.25.75-1.75V14.5M9 20v-2.5c0-.75-.75-1.25-.75-1.75V14.5M11 20v-2.5c0-.75.75-1.25.75-1.75V14.5M14 20v-2.5c0-.75-.75-1.25-.75-1.75V14.5M18.5 9v6");
}

</style>
