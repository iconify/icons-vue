<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o6ak7vbfp"/><path class="f6_7b22_l"/><path class="wtoegrbgv"/><path class="orx8z1bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-proton-7" /></template>
<style>
.f6_7b22_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 25.793v-13.93a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v24.275a4 4 0 0 0 4 4");
}

.o6ak7vbfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.76 33.909l8.062-15h-9.937");
}

.orx8z1bik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.207 40.138V15.819a3.14 3.14 0 0 0-3.138-3.138H4.5");
}

.wtoegrbgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 36.138V11.862a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v24.276a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

</style>
