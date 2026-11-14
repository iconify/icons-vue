<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hn30vywcg"/><path class="g8bcq4b5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lighting-curfew" /></template>
<style>
.g8bcq4b5a {
  d: path("M10.5 7.5a2.5 2.5 0 0 1 5 0Zm9-3.5h.01m1.99 14a4 4 0 1 1-5-4.5a3.5 3.5 0 0 0 5 4.5");
}

.hn30vywcg {
  d: path("M4 21.5h6m-3 0v-15a3 3 0 0 1 3-3h3V5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
