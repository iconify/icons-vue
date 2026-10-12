<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xnlxbbbyx"/><path class="ab3f_noey"/><circle class="apaf5vfgj"/><path class="hjuagz2ni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flamingo-sharp" /></template>
<style>
.ab3f_noey {
  d: path("M9.75 10.25L5.433 8.68L7.25 5.5");
}

.apaf5vfgj {
  cx: 8.5px;
  cy: 4.5px;
  r: 1.5px;
}

.hjuagz2ni {
  d: path("m10 3.25l2 1l.814.407l-.464.743l-1.1 1.6l-1.6-2.25Zm4.5 11V21m0-3.25L12 16");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xnlxbbbyx {
  d: path("M9 11c0-2.5 2.5-4 5.5-4s5.75 1.5 5.75 3.25v1l-1-.5L16 13.5l-1.125.75H13.25C10.75 14.25 9 13 9 11Z");
}

</style>
