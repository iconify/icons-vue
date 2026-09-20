<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mep3kqq1w"/><path class="sc8uzabfq"/><path class="ouo6kyg4x"/><path class="yci4i4bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:debloater" /></template>
<style>
.mep3kqq1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.89 18.944L14.68 43.5h20.092l2.79-24.556Z");
}

.ouo6kyg4x {
  fill: currentColor;
  d: path("M14.253 13.747a.75.75 0 1 1 1.06 0a.75.75 0 0 1-1.06 0m3.822 3.822a.75.75 0 1 1 1.06 0a.75.75 0 0 1-1.06 0");
}

.sc8uzabfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 4.75;
  d: path("M37.562 18.944L16.987 4.5");
}

.yci4i4bxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.516 18.944a6.62 6.62 0 0 0-1.44-7.206a6.62 6.62 0 0 0-9.362 0a.945.945 0 0 0 0 1.336l5.87 5.87m.15-11.948l-.236 2.895m8.32 5.189l-2.895.236");
}

</style>
