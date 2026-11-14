<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a-p6as2ow"/><path class="uni_q5bqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drawknife" /></template>
<style>
.a-p6as2ow {
  d: path("M8.25 6.5h7.5L14.5 11h-5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uni_q5bqd {
  d: path("M6.847 4.53za1.75 1.75 0 0 1 1.42 2.028l-1.823 10.34a1.75 1.75 0 0 1-2.028 1.42a1.75 1.75 0 0 1-1.419-2.028L4.82 5.95a1.75 1.75 0 0 1 2.027-1.42m10.306 0za1.75 1.75 0 0 1 2.027 1.42l1.823 10.34a1.75 1.75 0 0 1-1.419 2.028a1.75 1.75 0 0 1-2.028-1.42l-1.823-10.34a1.75 1.75 0 0 1 1.42-2.028");
}

</style>
