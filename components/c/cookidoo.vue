<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n4njpsm1t"/><path class="ddz_9_b_l"/><path class="jf4zsobra"/><circle class="hrmx0xb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cookidoo" /></template>
<style>
.ddz_9_b_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.824 9.715c-.647 2.638-2.495 5.184-4.581 7.712l-16.285-.126c-2.344-2.349-4.546-4.78-5.567-7.901m21.852 8.027c3.13.049 5.458 3.55 4.41 9.006c-1.028 5.359-5.771 15.119-12.552 16.68c-3.196.735-6.633-.043-9.947-.168c-5.844-.221-5.989-5.434-4.827-9.695c1.137-4.17 6.64-11.92 6.64-11.92");
}

.hrmx0xb-s {
  cx: 26.409px;
  cy: 38.727px;
  r: 1.317px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jf4zsobra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.959 17.301l.42 9.989c.378 9.037 10.668 7.26 13.724-.671c1.264-3.282 1.007-9.2 1.007-9.2M15.12 35.39l8.98.378l-1.51 5.54l-9.36-.546Zm20.69-5.891c.176 3.744.363 7.26.21 11.85a30.74 30.74 0 0 1-13.578 2.019");
}

.n4njpsm1t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.926 4.5a40.4 40.4 0 0 0-12.508 2.225c-7.01 2.323-1.032 2.685.504 2.686c5.41.004 14.791-.006 22.832.168c1.901.04 11.43.97 4.91-2.35C33.882 4.794 28.25 4.489 22.925 4.5");
}

</style>
