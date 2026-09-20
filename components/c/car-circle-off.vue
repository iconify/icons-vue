<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="rz6f9bczc"/><path class="zo1clobkc"/><path clip-rule="evenodd" class="pn5kx0b7g"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:car-circle-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.pn5kx0b7g {
  fill-rule: evenodd;
  d: path("M15.195 8h-4.39a2 2 0 0 0-1.956 1.58l-.429 2A2 2 0 0 0 10.376 14h5.248a2 2 0 0 0 1.955-2.42l-.429-2A2 2 0 0 0 15.195 8m-4.82 4l.43-2h4.39l.429 2z");
}

.rz6f9bczc {
  fill-rule: evenodd;
  d: path("M8.653 5.79a2.5 2.5 0 0 0-1.837 1.823l-1.13 4.523A2.5 2.5 0 0 0 4 14.5v3A2.5 2.5 0 0 0 6.5 20h13a2.5 2.5 0 0 0 2.5-2.5v-3a2.5 2.5 0 0 0-1.685-2.364l-1.131-4.523a2.5 2.5 0 0 0-1.836-1.823A18.4 18.4 0 0 0 13 5.263q-2.175 0-4.348.527M6.5 14a1 1 0 0 0 .97-.758l1.286-5.144a.5.5 0 0 1 .368-.365A16.4 16.4 0 0 1 13 7.263a16.4 16.4 0 0 1 3.876.47a.5.5 0 0 1 .367.365l1.286 5.144a1 1 0 0 0 .97.758a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-.5.5h-13a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 1 .5-.5");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.zo1clobkc {
  d: path("M19.5 16a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m-10 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0M7 18.5A1.5 1.5 0 0 1 8.5 20v1a1.5 1.5 0 0 1-3 0v-1A1.5 1.5 0 0 1 7 18.5m12 0a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-3 0v-1a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
