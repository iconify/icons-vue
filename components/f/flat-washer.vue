<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t42ot7bfe"/><path class="yev75xqlb"/><path class="dqqdq_23d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flat-washer" /></template>
<style>
.dqqdq_23d {
  d: path("M8.5 10.5a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0Z");
}

.t42ot7bfe {
  d: path("M3 10.5a9 5.5 0 1 0 18 0a9 5.5 0 1 0-18 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yev75xqlb {
  d: path("M3 10.5V13a9 5.5 0 0 0 18 0v-2.5");
}

</style>
