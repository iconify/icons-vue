<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d_hms9f2e"/><path class="zgfln6bre"/><path class="bra6jib7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blood-type" /></template>
<style>
.bra6jib7t {
  fill: currentColor;
  d: path("M15 19h6c0 1.6-1.4 2.75-3 2.75S15 20.6 15 19");
}

.d_hms9f2e {
  d: path("M2.75 14.5L6 4h1.5l3.25 10.5M4.5 11H9m4.25 3.5V4h3c1.75 0 3 1.25 3 2.75s-1.25 2.5-3 2.5h-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zgfln6bre {
  d: path("M16.25 9.25H17c1.75 0 3 1.25 3 2.75v.032M14.076 14.5h-.826M18 14c1.75 2 3 3.5 3 5c0 1.6-1.4 2.75-3 2.75S15 20.6 15 19c0-1.5 1.25-3 3-5");
}

</style>
