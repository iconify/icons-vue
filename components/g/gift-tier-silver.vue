<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r39aqe9xd"/><path class="os6i88c9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gift-tier-silver" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.os6i88c9m {
  d: path("m12.441 12.768l.088.205a1.5 1.5 0 0 0 1.235.897l.222.021a.48.48 0 0 1 .273.839l-.167.147a1.5 1.5 0 0 0-.472 1.452l.048.217a.48.48 0 0 1-.713.519l-.192-.114a1.5 1.5 0 0 0-1.526 0l-.192.114a.48.48 0 0 1-.713-.519l.048-.217a1.5 1.5 0 0 0-.472-1.452l-.167-.147a.48.48 0 0 1 .273-.839l.222-.021a1.5 1.5 0 0 0 1.235-.897l.088-.205a.48.48 0 0 1 .882 0");
}

.r39aqe9xd {
  d: path("M5.75 15a6.25 6.25 0 1 0 12.5 0a6.25 6.25 0 1 0-12.5 0M6.5 2.75l3 6.5m8-6.5l-3 6.5");
}

</style>
