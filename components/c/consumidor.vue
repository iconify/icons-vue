<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k18x8kbzy"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:consumidor" /></template>
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

.k18x8kbzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.074 29.311V17.69h3.78a3.922 3.922 0 0 1 0 7.845h-3.78M9.645 28.003c.7.882 1.784 1.37 2.908 1.307h1.745a2.905 2.905 0 0 0 0-5.81h-1.89a2.906 2.906 0 0 1-.034-5.812h1.779a3.12 3.12 0 0 1 2.908 1.308M38.5 25.461a3.926 3.926 0 0 1-7.851 0V21.54a3.91 3.91 0 0 1 3.892-3.922h.033a3.787 3.787 0 0 1 3.78 3.922");
}

</style>
