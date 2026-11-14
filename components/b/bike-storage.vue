<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nl6phzbyd"/><path class="darf42zvs"/><path class="qi224cc5k"/><path class="xnegxmcgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-storage" /></template>
<style>
.darf42zvs {
  d: path("M11.75 17.75a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nl6phzbyd {
  d: path("M2.5 9L21 3.5v18M2.75 17.75a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.qi224cc5k {
  d: path("M6.25 17.75h4.25l3-5.25l1.75 5.25");
}

.xnegxmcgs {
  d: path("m6.25 17.75l2.5-5.25h4.75m-4.75 0V11M7.5 11H10m3.5 1.5l-.5-1.75h1.75");
}

</style>
