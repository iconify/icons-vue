<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u26yxeb1u"/><path class="lj3f39e-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baseball-diamond" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lj3f39e-p {
  fill: currentColor;
  d: path("M12.875 2.875za1.237 1.237 0 0 1 0 1.75a1.237 1.237 0 0 1-1.75 0a1.237 1.237 0 0 1 0-1.75a1.237 1.237 0 0 1 1.75 0m8.25 8.25za1.237 1.237 0 0 1 0 1.75a1.237 1.237 0 0 1-1.75 0a1.237 1.237 0 0 1 0-1.75a1.237 1.237 0 0 1 1.75 0m-16.5 0za1.237 1.237 0 0 1 0 1.75a1.237 1.237 0 0 1-1.75 0a1.237 1.237 0 0 1 0-1.75a1.237 1.237 0 0 1 1.75 0M10.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.u26yxeb1u {
  d: path("m13.061 4.561l6.378 6.378a1.5 1.5 0 0 1 0 2.122l-6.378 6.378a1.5 1.5 0 0 1-2.122 0l-6.378-6.378a1.5 1.5 0 0 1 0-2.122l6.378-6.378a1.5 1.5 0 0 1 2.122 0");
}

</style>
