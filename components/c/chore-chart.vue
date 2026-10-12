<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="d_32uqbun"/><path class="j6hkc6ivy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chore-chart" /></template>
<style>
.d_32uqbun {
  width: 18px;
  height: 18.25px;
  x: 3px;
  y: 3px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6hkc6ivy {
  d: path("M3 12h18M9.25 3v18.25M13.5 7.5l1.25 1.25l2.5-2.5m-2 8.57l.37.81q.12.27.42.3l.88.11q.3.03.08.23l-.66.6q-.22.2-.16.5l.18.87q.06.29-.2.14l-.77-.43q-.26-.15-.53 0l-.77.43q-.26.15-.2-.14l.18-.87q.06-.3-.16-.5l-.66-.6q-.22-.2.08-.23l.88-.11q.3-.03.42-.3l.37-.81q.13-.27.25 0");
}

</style>
