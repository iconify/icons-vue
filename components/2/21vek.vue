<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nsv4zus_z"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:21vek" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.nsv4zus_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.284 20.864l2.155-1.174v8.62m6.506-5.711L23.79 28.31l-2.155-5.711M34.19 19.69v8.62m.001-1.831l3.902-3.883m-2.66 2.647l3.067 3.054m-6.795-1.075a2.155 2.155 0 0 1-4.027-1.067v-1.4a2.155 2.155 0 1 1 4.31 0v.7h-4.31M9.5 22.546a2.858 2.858 0 0 1 3.422-2.801c1.197.23 2.153 1.266 2.272 2.479c.09.903-.197 1.793-.82 2.34C13.219 25.578 9.5 28.31 9.5 28.31h5.71");
}

</style>
