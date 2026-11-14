<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="leoj6bcuj"/><path class="u402xnbet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:api-versioning" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.leoj6bcuj {
  d: path("M6.5 2.5h11A3.5 3.5 0 0 1 21 6v1.5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 7.5V6a3.5 3.5 0 0 1 3.5-3.5m0 11.25h11a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 18v-.75a3.5 3.5 0 0 1 3.5-3.5");
}

.u402xnbet {
  d: path("m6.5 5.25l1.75 3l1.75-3m3 1.5h4.5m-11 11H11");
}

</style>
