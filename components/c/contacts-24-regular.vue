<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q0j4e5n0l"/><path class="xfudylzqp"/><path class="wxnc4acnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:contacts-24-regular" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.q0j4e5n0l {
  d: path("M15.5 12.25a.75.75 0 0 0-.75-.75h-5a.75.75 0 0 0-.75.75v.5c0 1 1.383 1.75 3.25 1.75s3.25-.75 3.25-1.75v-.5z");
  fill: currentColor;
}

.wxnc4acnn {
  d: path("M4 4.5A2.5 2.5 0 0 1 6.5 2H18a2.5 2.5 0 0 1 2.5 2.5v14.25a.75.75 0 0 1-.75.75H5.5a1 1 0 0 0 1 1h13.25a.75.75 0 0 1 0 1.5H6.5A2.5 2.5 0 0 1 4 19.5v-15zm1.5 0V18H19V4.5a1 1 0 0 0-1-1H6.5a1 1 0 0 0-1 1z");
  fill: currentColor;
}

.xfudylzqp {
  d: path("M14 8.745C14 7.78 13.217 7 12.25 7s-1.75.779-1.75 1.745a1.75 1.75 0 1 0 3.5 0z");
  fill: currentColor;
}

</style>
