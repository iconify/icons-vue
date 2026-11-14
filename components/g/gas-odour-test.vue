<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q4mewvbln"/><path class="rdr7p9b6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gas-odour-test" /></template>
<style>
.q4mewvbln {
  d: path("M16.5 2.5c-.5 5.5-4.5 9-6 12.5c-1 3 .5 5.5 3 5.5H16");
}

.rdr7p9b6s {
  d: path("M13 17.5a1.5 1.5 0 0 1 3 0M3 8q1.5-1.5 3 0t3 0t3 0m-9.5 5q1.5-1.5 3 0t3 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
