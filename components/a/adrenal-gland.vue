<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="muzg2o2fj"/><path class="u2l6xpbqj"/><path class="rx3gxnn5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:adrenal-gland" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.muzg2o2fj {
  d: path("M12.25 6.25C8.5 6.25 6 9.5 6 13.5s2.5 7.25 6.25 7.25c2.25 0 3.75-1.25 3.25-3.25c-.5-1.5-2.25-2.25-2.25-4S15 11 15.5 9.5c.5-2-1-3.25-3.25-3.25");
}

.rx3gxnn5f {
  d: path("M13.25 13.5h5");
}

.u2l6xpbqj {
  fill: currentColor;
  d: path("m11.135 4.906l2.598-.093A.769.769 0 0 0 14.25 3.5l-.415-.415a1.5 1.5 0 0 0-1.843-.219l-1.242.759a.691.691 0 0 0 .385 1.281");
}

</style>
