<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wv6_i6q5n"/><path class="dk0wg0b7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:home-battery" /></template>
<style>
.dk0wg0b7e {
  d: path("M10.5 12h.25v-1.25h2.5V12h.25a1.25 1.25 0 0 1 1.25 1.25v4a1.25 1.25 0 0 1-1.25 1.25h-3a1.25 1.25 0 0 1-1.25-1.25v-4A1.25 1.25 0 0 1 10.5 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wv6_i6q5n {
  d: path("M3.25 19.75v-7.5q0-1.5 1.14-2.48l6.47-5.54q1.14-.98 2.28 0l6.47 5.54q1.14.98 1.14 2.48v7.5q0 1.5-1.5 1.5H4.75q-1.5 0-1.5-1.5");
}

</style>
