<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om1svdb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:contour-map-mine" /></template>
<style>
.om1svdb1y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.771 3.627q-3.198-1.704-5.864-1.371q-3.191.399-5.544 3.199q-2.189 2.606-2.605 5.939q-1.076 7.526 4.627 8.347q1.055.178 2.844 1.132q3.198 1.704 5.864 1.371q.027-.003.054-.009q4.127-.825 5.25-5.379q.41-1.661.784-2.541q1.292-2.6.743-5.457q-.618-3.213-3.187-4.07q-.056-.018-.114-.028q-1.056-.176-2.852-1.133m-2.635 5.605q.447.268.614.268q.122 0 .237.038q.964.322 1.215 1.492q.22 1.026-.298 1.84q-.11.231-.237.649q-.44 1.442-1.753 1.713q-.969.233-2.117-.485q-.285-.178-.449-.251q-1.085-.066-1.509-1.083q-.316-.757-.088-1.755q.05-2.545 2.906-2.902q.046-.006.093-.006q.583 0 1.386.482");
}

</style>
