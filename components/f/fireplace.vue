<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwe41bbpc"/><path class="h2fw37b2o"/><path class="fsh4emkvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fireplace" /></template>
<style>
.fsh4emkvk {
  d: path("M12 14.25c1 .9 1.6 1.9 1.6 2.9a1.6 1.6 0 0 1-3.2 0c0-1 .6-2 1.6-2.9");
}

.h2fw37b2o {
  d: path("M7.75 21.25V14.5a4.25 4.25 0 0 1 8.5 0v6.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pwe41bbpc {
  d: path("M2.75 5.25h18.5m-16.5 2.5h14.5v13.5H4.75Z");
}

</style>
