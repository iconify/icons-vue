<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z9zlatbjf"/><path class="gnymwcb8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:function-graph" /></template>
<style>
.gnymwcb8y {
  d: path("M8.5 16.25c1.75-9.75 4.25-9.75 5.75-5s3.5 5.25 6.5-5.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z9zlatbjf {
  d: path("M4.75 2.75v15.5a3 3 0 0 0 3 3h13.5");
}

</style>
