<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hv9exrb3q"/><path class="lpw076b9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basket-produce-full" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hv9exrb3q {
  d: path("M6.202 10h11.596a2.625 2.625 0 0 1 2.574 3.14l-.95 4.75A2.625 2.625 0 0 1 16.848 20H7.152a2.625 2.625 0 0 1-2.574-2.11l-.95-4.75A2.625 2.625 0 0 1 6.202 10");
}

.lpw076b9m {
  d: path("M5 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0m8 3c0-4 2-6.5 6-7c0 4-2 6.5-6 7m-4 3v4m6-4v4");
}

</style>
