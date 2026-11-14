<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b8fr_cfzg"/><path class="us0v95o-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:load-balancer" /></template>
<style>
.b8fr_cfzg {
  d: path("M2.5 12h3c2.5 0 2.5-5.25 5-5.25h1.75M5.5 12c2.5 0 2.5 5.25 5 5.25h1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.us0v95o-e {
  d: path("m10.5 4.75l2 2l-2 2m0 6.5l2 2l-2 2m7.375-16h1.25a2.625 2.625 0 0 1 2.625 2.625v1.75a2.625 2.625 0 0 1-2.625 2.625h-1.25a2.625 2.625 0 0 1-2.625-2.625v-1.75a2.625 2.625 0 0 1 2.625-2.625m0 10.5h1.25a2.625 2.625 0 0 1 2.625 2.625v1.75a2.625 2.625 0 0 1-2.625 2.625h-1.25a2.625 2.625 0 0 1-2.625-2.625v-1.75a2.625 2.625 0 0 1 2.625-2.625");
}

</style>
