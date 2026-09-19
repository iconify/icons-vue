<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="waxl1bbyz"/><path class="p9k1vy3xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coronalert" /></template>
<style>
.p9k1vy3xx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.769 32.295a2.113 2.113 0 0 0 4.055 0M21 2.5h6m-3 0v5.089m21.5 12.769v6m0-3h-5.089m-37.911 3v-6m0 3h5.089M27 45.5h-6m3 0v-5.089M37.359 8.549l2.119 2.124m-1.06-1.062l-1.801 1.797m2.834 25.951l-2.124 2.119m1.062-1.06l-1.797-1.801m-25.951 2.834l-2.119-2.124m1.06 1.062l1.801-1.797M8.549 10.641l2.124-2.119m-1.062 1.06l1.797 1.801");
}

.waxl1bbyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.562 28.419v-6.177a7.54 7.54 0 0 0-5.509-7.244v-.605a2.053 2.053 0 1 0-4.106 0v.605a7.54 7.54 0 0 0-5.509 7.244v6.177l-1.814 2.892a.642.642 0 0 0 .544.984h17.257a.642.642 0 0 0 .577-.924Z");
}

</style>
