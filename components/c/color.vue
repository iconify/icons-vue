<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ea09qzj-g"/><path class="btz19ujmj"/><path class="wul9ap_cf"/><path class="qu87ogpfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:color" /></template>
<style>
.btz19ujmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.44 35.359c6.031-3.032 10.885-11.038 8.529-18.998c-8.44.544-14.312 8.233-14.825 15.098");
}

.ea09qzj-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 8.896c-9.448 7.539-7.734 22.976 0 27.744c7.734-4.768 9.448-20.205 0-27.744");
}

.qu87ogpfk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.113 37.94c-5 2.58-13.418.92-16.613-5.463c3.22-2.594 7.36-3.05 10.953-2.132");
}

.wul9ap_cf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.56 35.359C12.53 32.327 7.676 24.32 10.032 16.36c8.44.544 14.312 8.233 14.825 15.098m1.03 6.482c5 2.58 13.418.92 16.613-5.463c-3.22-2.594-7.36-3.05-10.953-2.132");
}

</style>
