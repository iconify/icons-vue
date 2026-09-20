<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="wssyiwwsp"/><path class="jsg7s-bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:efatura" /></template>
<style>
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

.jsg7s-bug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.02 29.96a6.144 6.144 0 0 1-10.846-3.955v-6.033a6.144 6.144 0 0 1 6.143-6.144c1.898 0 3.595.86 4.722 2.213m-13.156 4.721h6.871m-6.871 4.496h6.871m10.335 8.499h-2.516m-.623 1.882l1.881-5.68l1.881 5.68m.777-5.655h3.683m-1.842 5.559v-5.559");
}

.wssyiwwsp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.685 24.79a2 2 0 0 1-3.738-.99v-1.3a2 2 0 1 1 4 0v.65h-4");
}

</style>
