<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="bc1r9vbev"/><path class="v26f_f5yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:efatura" /></template>
<style>
.bc1r9vbev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.685 24.79a2 2 0 0 1-1.738 1.01h0a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v.65h-4");
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

.v26f_f5yn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.02 29.96a6.13 6.13 0 0 1-4.703 2.189h0a6.144 6.144 0 0 1-6.144-6.144v-6.033a6.144 6.144 0 0 1 6.144-6.144h0c1.898 0 3.595.86 4.722 2.213m-13.156 4.721h6.871m-6.871 4.496h6.871m10.335 8.499h-2.516m-.623 1.882l1.881-5.68l1.881 5.68m.777-5.655h3.683m-1.842 5.559v-5.559");
}

</style>
