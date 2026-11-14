<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i0rnubbnc"/><path class="tz3zi0bjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bath-toys" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i0rnubbnc {
  d: path("M5 13a3.75 3.75 0 1 1 6.75-2c1.25 2.5 4.75 2.5 8.25.5c.5 5-3 8.5-7.5 8.5c-5 0-7.5-3-7.5-7");
}

.tz3zi0bjd {
  d: path("m12.594 7.73l.531.145a.453.453 0 0 1 .036.862l-.589.214a.613.613 0 0 1-.822-.576a.668.668 0 0 1 .844-.645M7.75 8.5h.01");
}

</style>
