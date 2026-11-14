<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ktc-bccqk"/><path class="tzslzyb2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hazard-class-5" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ktc-bccqk {
  d: path("m13.061 3.561l7.378 7.378a1.5 1.5 0 0 1 0 2.122l-7.378 7.378a1.5 1.5 0 0 1-2.122 0l-7.378-7.378a1.5 1.5 0 0 1 0-2.122l7.378-7.378a1.5 1.5 0 0 1 2.122 0");
}

.tzslzyb2o {
  d: path("M12 6.25c1.5 1.5 2 2.25 2 3a2 2 0 0 1-4 0c0-.75.5-1.5 2-3m-1.75 9.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
