<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n94xd8sxo"/><path class="gulrqe8fj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cpr" /></template>
<style>
.gulrqe8fj {
  d: path("M9 14c1 1.5 4 1.75 5.5.5M3 3v6M2 8l1 1l1-1m17-5v6m-1-1l1 1l1-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n94xd8sxo {
  d: path("M2.5 21.5C2.5 20 4 19.25 6 19.25h12c2 0 3.5.75 3.5 2.25M9 16.75V15l-2.5-3.75c-.5-.75-.25-1.5.25-1.75c.5-.5 1.25-.25 1.75.5l1 1.25v-6.5c0-.5.5-1 1-1s1.25.5 1.25 1V9V3.75c0-.75.5-1.25 1-1.25S14 3 14 3.75V9V4.75c0-.5.5-1 1-1s1.25.5 1.25 1v4.5v-2.5c0-.75.5-1.25 1-1.25s1.25.5 1.25 1.25V12c0 2.25-1.5 3.25-2.75 3.25v1.5");
}

</style>
