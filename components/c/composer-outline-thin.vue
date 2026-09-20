<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="murw5tb-p"/><path class="mi7pnccmc"/><path class="dpr_gnqpq"/><path class="h0hlbvfqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:composer-outline-thin" /></template>
<style>
.dpr_gnqpq {
  d: path("m14.5 14.5 4 -4");
}

.h0hlbvfqt {
  d: path("M15.5 10.5h3v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mi7pnccmc {
  d: path("M6 10v4");
}

.murw5tb-p {
  d: path("M2 9a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
