<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mi7qntj-k"/><path class="q03s1s14v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-datacenter" /></template>
<style>
.mi7qntj-k {
  d: path("M3 3h18v7.5H3Zm12.4 18H3v-7.5h18v1.9M7 6.75h.01M7 17.25h.01");
}

.q03s1s14v {
  d: path("M18.5 15.5q0 3 3 3q-3 0-3 3q0-3-3-3q3 0 3-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
