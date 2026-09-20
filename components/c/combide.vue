<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bk_4cbnsr"/><circle class="r49ybnb-i"/><path class="x-6se2boz"/><path class="cy-d7_i0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:combide" /></template>
<style>
.bk_4cbnsr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.448 27.294za2.09 2.09 0 0 1-2.084-2.084v-1.355a2.09 2.09 0 0 1 2.084-2.084a2.09 2.09 0 0 1 2.084 2.084v1.355a2.09 2.09 0 0 1-2.084 2.084m4.326-3.334a2.09 2.09 0 0 1 2.084-2.085a2.09 2.09 0 0 1 2.084 2.084v3.335m-4.168-5.419v5.419m4.168-3.334a2.09 2.09 0 0 1 2.084-2.085a2.09 2.09 0 0 1 2.084 2.084v3.335");
}

.cy-d7_i0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4");
}

.r49ybnb-i {
  cx: 37.666px;
  cy: 19.27px;
  r: 0.834px;
  fill: currentColor;
}

.x-6se2boz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.666 21.771v5.523m-15.284 3.917a6.95 6.95 0 0 1-5.909 3.25A6.944 6.944 0 0 1 9.5 27.544v-7.032a6.944 6.944 0 0 1 6.915-6.973h.058a6.55 6.55 0 0 1 5.965 3.693m9.016 6.623a2.09 2.09 0 0 1 2.084-2.084a2.09 2.09 0 0 1 2.084 2.084v1.355a2.09 2.09 0 0 1-2.084 2.084a2.09 2.09 0 0 1-2.084-2.084m0 2.084v-8.336");
}

</style>
