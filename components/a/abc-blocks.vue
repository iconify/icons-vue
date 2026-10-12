<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kyr19yuam"/><rect class="b6tz6bb5h"/><rect class="tkm6ldekt"/><path class="e1e0cdm7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:abc-blocks" /></template>
<style>
.b6tz6bb5h {
  width: 7.75px;
  height: 8px;
  x: 2.75px;
  y: 13.25px;
  rx: 1.5px;
}

.e1e0cdm7h {
  d: path("M10.25 11.25L12 7.5l1.75 3.75M10.85 10h2.3M7.9 15.65a2 2 0 1 0 0 3.2m7.6-3.6h4l-4 4h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kyr19yuam {
  width: 7.75px;
  height: 7.75px;
  x: 8.13px;
  y: 5.5px;
  rx: 1.5px;
}

.tkm6ldekt {
  width: 7.75px;
  height: 8px;
  x: 13.5px;
  y: 13.25px;
  rx: 1.5px;
}

</style>
