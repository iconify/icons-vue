<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q_bn4_bps"/><rect class="t-mk92b3a"/><rect class="r-cxamb8s"/><path class="krf4oq1ms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ci-pipeline" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.krf4oq1ms {
  d: path("M7.25 15h2.5m4.5 0h2.5m-12-4.75V8.5a3 3 0 0 1 3-3h8.5a3 3 0 0 1 3 3v1.75M17.5 8.5l1.75 1.75L21 8.5");
}

.q_bn4_bps {
  width: 4.5px;
  height: 5px;
  x: 2.75px;
  y: 12.5px;
  rx: 1.25px;
}

.r-cxamb8s {
  width: 4.5px;
  height: 5px;
  x: 16.75px;
  y: 12.5px;
  rx: 1.25px;
}

.t-mk92b3a {
  width: 4.5px;
  height: 5px;
  x: 9.75px;
  y: 12.5px;
  rx: 1.25px;
}

</style>
