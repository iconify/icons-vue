<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zzzutbcpr"/><path class="ihuvztbth"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-potable-water-symbol" /></template>
<style>
.ihuvztbth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.537 23.214L14.403 38.5h7.643l2.866-15.286");
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

.zzzutbcpr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.288 30.675s4.777-1.911 9.554 0m13.621-14.857v3.553c0 .409-.328.73-.73.73H23.42c-2.072 0-2.561 1.794-2.67 2.794a.726.726 0 0 1-.723.642h-3.662a.724.724 0 0 1-.73-.715c-.007-2.043.598-7.733 7.755-7.733h3.772v-3.247h-3.465V9.5h9.666v2.342h-3.465v3.246h5.837c.4 0 .73.329.73.73");
}

</style>
