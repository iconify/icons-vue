<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m6_15sjua"/><path class="bt500ze0l"/><path class="c97p9qq2v"/><path class="xy5uirmfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alza" /></template>
<style>
.bt500ze0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.065 16.735l25.634-6.326l5.113 25.765L12.178 42.5z");
}

.c97p9qq2v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.595 28.95c1.659 1.843 5.112-1.42 5.438-5.131c-3.002.315-8.03 2.163-5.438 5.13");
}

.m6_15sjua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.188 11.826L35.822 5.5l5.113 25.765l-25.634 6.326z");
}

.xy5uirmfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.856 19.586c.808-3.364-4.209-3.971-5.468-.711l-8.34-.242c3.488-8.828 22.572-11.527 22.66-2.806c-.173 3.782-2.315 13.105-2.255 15.072l.092 3.353l-8.354-.18l.105-2.854c-4.357 5.223-14.369 4.124-14.638-1.541c-.348-7.239 7.013-9.771 16.198-10.09Z");
}

</style>
