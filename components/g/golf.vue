<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="f1dfzwbmh"/><path class="lguww6bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:golf" /></template>
<style>
.f1dfzwbmh {
  cx: 24px;
  cy: 18.893px;
  r: 14.393px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lguww6bai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.843 35.762c2.721 1.48 5.841 2.322 9.157 2.322s6.436-.841 9.157-2.322m-6.655-10.493c.582-.172 1.131-.488 1.59-.947s.776-1.008.948-1.59m2.835 3.505c.522-.31.976-.75 1.308-1.31s.503-1.168.526-1.774m-7.839 6.382c.6.088 1.23.032 1.84-.192s1.128-.589 1.529-1.045M24 38.084V43.5");
}

</style>
