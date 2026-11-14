<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aj03wnz9n"/><path class="g3am0wbnu"/><path class="ouz06957u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:docket" /></template>
<style>
.aj03wnz9n {
  d: path("M6 10h6a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-4.5A3.5 3.5 0 0 1 6 10");
}

.g3am0wbnu {
  d: path("M5.5 10V8.5a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2V18h-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ouz06957u {
  d: path("M8.5 6.5V5a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v9.5h-3m-13-1h4");
}

</style>
