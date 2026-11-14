<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rq_kn7bnn"/><path class="yy5unzblq"/><path class="ytumn967e"/><path class="r89owkgvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heat-pump-cycle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r89owkgvx {
  d: path("m13.75 17.5l-2 2l2 2");
}

.rq_kn7bnn {
  d: path("M9.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.ytumn967e {
  d: path("m10.25 2.5l2 2l-2 2m10.75 7v3a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-3");
}

.yy5unzblq {
  d: path("M3 10.5v-3a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v3");
}

</style>
