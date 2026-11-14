<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h95erkwan"/><path class="blri9eb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:badger" /></template>
<style>
.blri9eb6c {
  d: path("M6.375 8.199a2.25 2.25 0 0 1-2.25-3.898m13.5 3.898a2.25 2.25 0 0 1 2.25-3.898M10 5.5l.75 9q1.25 1.5 2.5 0l.75-9M6.75 11h.01m10.49 0h.01");
}

.h95erkwan {
  d: path("M10.5 20.5h3c2-3.5 7.5-6 7.5-10.5c0-3.5-4-4.5-9-4.5s-9 1-9 4.5c0 4.5 5.5 7 7.5 10.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
