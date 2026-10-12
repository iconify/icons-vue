<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wv6_i6q5n"/><path class="t5oj_94rs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eco-house" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t5oj_94rs {
  d: path("M8.75 18.25c.25-4.02 1.95-5.75 6.5-5.75c-.25 4.02-1.95 5.75-6.5 5.75");
}

.wv6_i6q5n {
  d: path("M3.25 19.75v-7.5q0-1.5 1.14-2.48l6.47-5.54q1.14-.98 2.28 0l6.47 5.54q1.14.98 1.14 2.48v7.5q0 1.5-1.5 1.5H4.75q-1.5 0-1.5-1.5");
}

</style>
