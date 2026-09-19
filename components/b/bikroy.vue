<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="y23gbx7tt"/><circle class="lzp31q9lr"/><circle class="qy522v5wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bikroy" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.lzp31q9lr {
  cx: 18.734px;
  cy: 17.828px;
  r: 2.027px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qy522v5wf {
  cx: 29.266px;
  cy: 17.828px;
  r: 2.027px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y23gbx7tt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.195 23.351c.498 0 .887.422.864.919c-.259 5.648-4.783 9.794-10.059 9.794c-5.271 0-9.797-4.239-10.06-9.794a.87.87 0 0 1 .865-.919z");
}

</style>
