<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0_72tbrl"/><path class="spy07ybot"/><path class="e2nnbnb5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:layers" /></template>
<style>
.e2nnbnb5l {
  d: path("m3 16l9 5l9-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0_72tbrl {
  d: path("m12.85 3.472l5.396 2.998a1.75 1.75 0 0 1 0 3.06l-5.396 2.998a1.75 1.75 0 0 1-1.7 0L5.754 9.53a1.75 1.75 0 0 1 0-3.06l5.396-2.998a1.75 1.75 0 0 1 1.7 0");
}

.spy07ybot {
  d: path("m3 12l9 5l9-5");
}

</style>
