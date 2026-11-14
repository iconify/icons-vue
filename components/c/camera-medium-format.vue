<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dectabbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-medium-format" /></template>
<style>
.dectabbbf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 2.25h-3.5q-2.5 0-2.5 2.5v2q0 .883.312 1.454q-.574.298-1.067.791Q1.75 10.24 1.75 12v5.5q0 1.76 1.245 3.005T6 21.75h12q1.76 0 3.005-1.245T22.25 17.5V12q0-1.76-1.245-3.005T18 7.75h-5.877q.127-.436.127-1v-2q0-2.5-2.5-2.5m-.5 12.5q0-1.76 1.245-3.005T13.5 10.5t3.005 1.245t1.245 3.005t-1.245 3.005T13.5 19t-3.005-1.245T9.25 14.75");
}

</style>
