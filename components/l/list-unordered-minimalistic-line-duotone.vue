<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cssq9mzyi"/><path class="i2fyp1btn"/><path class="u3oqugmqn"/><path class="akly-1bxp"/><path class="tlafrnbwh"/><path class="ags-59u9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-unordered-minimalistic-line-duotone" /></template>
<style>
.ags-59u9n {
  d: path("M5 16H5.0001");
}

.akly-1bxp {
  d: path("M5 6H5.0001");
}

.cssq9mzyi {
  d: path("M10 6H20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2fyp1btn {
  d: path("M10 11H20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.tlafrnbwh {
  d: path("M5 11H5.0001");
}

.u3oqugmqn {
  d: path("M10 16H20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
