<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jrab_8kuu"/><path class="w8aubqbpu"/><path class="ym4i7flyo"/><path class="irp99fbld"/><path class="g-ai49bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fiio-cast" /></template>
<style>
.g-ai49bzz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.712 24.299c2.971-4.748 8.264-7.905 14.288-7.905s11.317 3.157 14.288 7.905");
}

.irp99fbld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.555 28.071C14.54 23.73 18.916 20.712 24 20.712s9.46 3.018 11.445 7.36");
}

.jrab_8kuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.303 35.395H8.5a4 4 0 0 1-4-4V14.711a4.65 4.65 0 0 1 4.643-4.643h29.714a4.65 4.65 0 0 1 4.643 4.643v16.684a4 4 0 0 1-4 4h-8.803");
}

.w8aubqbpu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 32.318l-5.02 5.614h10.041z");
}

.ym4i7flyo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.945 32.54c.36-4.132 3.83-7.36 8.055-7.36s7.696 3.228 8.056 7.36");
}

</style>
