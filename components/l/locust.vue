<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="o7ij0jbnw"/><path class="rr8krrbmo"/><path class="r776bxbjn"/><path class="vlkc8dbzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:locust" /></template>
<style>
.o7ij0jbnw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.52 12.53l.46-.31Q6 11.5 7.25 11.5h7q1.25 0 2.19-.82l.12-.11q.94-.82 2.16-.54l.81.19q1.22.28 1.41 1.52l.12.77q.19 1.24-.8 2.01l-.27.21q-.99.77-2.24.77h-2q-1.25 0-2.5-.11l-6-.53q-1.25-.11-2.32-.75l-.36-.22q-1.07-.64-.05-1.36");
}

.r776bxbjn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.75 12.5h.01");
}

.rr8krrbmo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 11.5C13.5 9.25 8.5 7.25 3.75 7.75a.75.75 0 0 0-.3 1.4L7.5 11.5Z");
}

.vlkc8dbzg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 15.5L9.5 20l-4.5.25M18.75 9.9c.25-2 1-3.25 2.25-4");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
