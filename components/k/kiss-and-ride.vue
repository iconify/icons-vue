<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-ms57juw"/><path class="dyrcmmzjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kiss-and-ride" /></template>
<style>
.dyrcmmzjy {
  d: path("M12 18.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.75 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x-ms57juw {
  d: path("M3 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-.5 15.5v-7a3 3 0 0 1 6 0v7m2.75-5.25v-1.298a1.44 1.44 0 0 1 .875-1.327l.209-.089a1.75 1.75 0 0 0 .935-.959L14.06 9.6a1.75 1.75 0 0 1 1.625-1.1h1.88a1.75 1.75 0 0 1 1.625 1.1l.841 2.103a1.75 1.75 0 0 0 .725.85l.119.072a1.29 1.29 0 0 1 .625 1.104v1.521A1.75 1.75 0 0 1 19.75 17H13a1.75 1.75 0 0 1-1.75-1.75");
}

</style>
