<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a07z7yf4n"/><path class="q0c57-bqm"/><path class="cpkdnxbfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:endless-runner" /></template>
<style>
.a07z7yf4n {
  d: path("M13 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.cpkdnxbfo {
  d: path("m8.5 10.75l4-1.75l4.5.5m-14.5 12h7V18H14v3.5h7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q0c57-bqm {
  d: path("M14 6.25L11 12l4.5 1l1 3.5M11 12l-3 2.5l-3.5-1");
}

</style>
