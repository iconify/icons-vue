<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="a_8a95-9e"/><path class="wa02njqms"/><circle class="a1sajjcke"/><path class="mrr0nn0wj"/><path class="uxjinbzjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:device-help" /></template>
<style>
.a_8a95-9e {
  cx: 30.798px;
  cy: 30.458px;
  r: 0.75px;
  fill: currentColor;
}

.a1sajjcke {
  cx: 30.659px;
  cy: 24.643px;
  r: 9.826px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mrr0nn0wj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.786 36.664V40.5c0 1.105-.564 2-1.258 2H8.773c-.694 0-1.257-.895-1.257-2v-33c0-1.105.563-2 1.257-2h20.755c.695 0 1.258.895 1.258 2v7.13");
}

.uxjinbzjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.65 25.428h-2.054l-1.714-4.8l-1.16 4.773l-1.173 4.829l-1.713-4.8h-1.679m5.341-15.988h5.334");
}

.wa02njqms {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.213 22.52c0-.99.401-1.887 1.05-2.536a3.585 3.585 0 0 1 6.12 2.535c0 .99-.334 1.961-1.05 2.535c-.742.595-2.548 1.57-2.548 3.087");
}

</style>
