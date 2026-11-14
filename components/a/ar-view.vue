<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pnrisabcr"/><path class="q9sdubo-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ar-view" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pnrisabcr {
  d: path("m12.723 6.398l3.5 1.925A1.5 1.5 0 0 1 17 9.637v4.726a1.5 1.5 0 0 1-.777 1.314l-3.5 1.925a1.5 1.5 0 0 1-1.446 0l-3.5-1.925A1.5 1.5 0 0 1 7 14.363V9.637a1.5 1.5 0 0 1 .777-1.314l3.5-1.925a1.5 1.5 0 0 1 1.446 0");
}

.q9sdubo-y {
  d: path("m7 8.75l5 2.75l5-2.75m-5 2.75V18M2.5 7V4.5a2 2 0 0 1 2-2H7m10 0h2.5a2 2 0 0 1 2 2V7m0 10v2.5a2 2 0 0 1-2 2H17m-10 0H4.5a2 2 0 0 1-2-2V17");
}

</style>
