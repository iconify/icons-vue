<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="he4lb0xkm"/><path class="px26bgbmk"/><path class="sinzrabrk"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:beeline" /></template>
<style>
.he4lb0xkm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.543 14.26c7.304-4.532 13.843-5.328 15.33-2.26c.891 5.414-9.184 11.624-15.373 12.42m.085 10.256c13.472-1.486 30.193-14.789 22.421-21.997c17.634 9.618 2.846 25.299-11.911 29.704");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.px26bgbmk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.554 42.5c6.349-5.531 7.251-8.535 7.697-12.378c-.095 5.223-1.752 9.47-4.066 12.261");
}

.sinzrabrk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.695 18.571c3.248 5.138 3.556 8.928 3.567 11.827M15.723 10.227c6.158-.425 9.141.594 12.634 2.654");
}

</style>
