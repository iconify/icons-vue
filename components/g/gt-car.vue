<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rcmfte2wa"/><path class="j3trcei8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gt-car" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j3trcei8i {
  d: path("M4.5 14.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m10 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-12-7H5m-.5 0V11");
}

.rcmfte2wa {
  d: path("M4.5 14.5h-2v-2.75l6-2.25l3-2.75h4L19 9.5l2.5.5v4.5h-2m-5 0h-5");
}

</style>
