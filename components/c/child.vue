<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="t02-z8bti"/><path class="p5zufp2xg"/><circle class="z_28vwb8i"/><path class="o3hv5guuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:child" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o3hv5guuh {
  d: path("M18.25 8.25c-.75 1.5.75 3 0 4.5");
}

.p5zufp2xg {
  d: path("M4.5 21.25h11a.75.75 0 0 0 .75-.75c0-2.2-2.81-3.75-6.25-3.75S3.75 18.3 3.75 20.5a.75.75 0 0 0 .75.75");
}

.t02-z8bti {
  cx: 10px;
  cy: 10.5px;
  r: 3.25px;
}

.z_28vwb8i {
  cx: 18.25px;
  cy: 5.75px;
  r: 2.5px;
}

</style>
