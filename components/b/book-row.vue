<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rnubghzqu"/><path class="f-vo6j0hh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:book-row" /></template>
<style>
.f-vo6j0hh {
  d: path("m12.514 8.025l.483-.13a1.75 1.75 0 0 1 2.144 1.238l2.588 9.659a1.75 1.75 0 0 1-1.238 2.143l-.482.13a1.75 1.75 0 0 1-2.144-1.238l-2.588-9.659a1.75 1.75 0 0 1 1.237-2.143M3.5 9.5h4M9 7h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rnubghzqu {
  d: path("M2.5 21h19M5.25 6h.5A1.75 1.75 0 0 1 7.5 7.75v11.5A1.75 1.75 0 0 1 5.75 21h-.5a1.75 1.75 0 0 1-1.75-1.75V7.75A1.75 1.75 0 0 1 5.25 6m5.5-2.5h.5A1.75 1.75 0 0 1 13 5.25v14A1.75 1.75 0 0 1 11.25 21h-.5A1.75 1.75 0 0 1 9 19.25v-14a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
