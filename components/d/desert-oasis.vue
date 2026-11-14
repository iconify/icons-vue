<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hzvv7l7zq"/><path class="aiy0qhc5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:desert-oasis" /></template>
<style>
.aiy0qhc5c {
  d: path("M4.5 16q7.5-5 15 0M4 19.5q2.5-1.5 5 0t5 0t5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hzvv7l7zq {
  d: path("M11.5 7q2 4 1 6.5m-1-6.5C9 4.5 6 4.5 3.5 6.5m8 .5c1.5-3 5.5-3.5 9-1.5");
}

</style>
