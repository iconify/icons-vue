<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f4o84dbpo"/><path class="ce4zcnw7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:company-newsletter" /></template>
<style>
.ce4zcnw7f {
  d: path("M7.25 6.5h9.5A1.25 1.25 0 0 1 18 7.75A1.25 1.25 0 0 1 16.75 9h-9.5A1.25 1.25 0 0 1 6 7.75A1.25 1.25 0 0 1 7.25 6.5M6 12h3.25M6 14.75h3.25M6 17.5h2.25m6.5-5.5H18m-3.25 2.75H18m-3.25 2.75H17");
}

.f4o84dbpo {
  d: path("M6.5 3.5h11A3.5 3.5 0 0 1 21 7v10a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17V7a3.5 3.5 0 0 1 3.5-3.5m5.5 8.25v8.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
