<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bw3xyfban"/><path clip-rule="evenodd" class="an_6_pbpk"/><path clip-rule="evenodd" class="h0efogboq"/><path clip-rule="evenodd" class="b27mptnyx"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:leave-circle-off" /></template>
<style>
.an_6_pbpk {
  fill-rule: evenodd;
  d: path("M18.027 16.768a1 1 0 0 1-.129-1.408l2.084-2.5a1 1 0 1 1 1.536 1.28l-2.083 2.5a1 1 0 0 1-1.408.128");
}

.b27mptnyx {
  fill-rule: evenodd;
  d: path("M16 5.5a1 1 0 0 1 1 1v4a1 1 0 1 1-2 0v-4a1 1 0 0 1 1-1m0 10a1 1 0 0 1 1 1v4a1 1 0 1 1-2 0v-4a1 1 0 0 1 1-1m-9-10a1 1 0 0 1 1 1v14a1 1 0 1 1-2 0v-14a1 1 0 0 1 1-1");
}

.bw3xyfban {
  fill-rule: evenodd;
  d: path("M18.027 10.232a1 1 0 0 1 1.408.128l2.083 2.5a1 1 0 0 1-1.536 1.28l-2.084-2.5a1 1 0 0 1 .128-1.408");
}

.cuyn6tgcc {
  fill: currentColor;
}

.h0efogboq {
  fill-rule: evenodd;
  d: path("M20.5 13.5a1 1 0 0 1-1 1H13a1 1 0 1 1 0-2h6.5a1 1 0 0 1 1 1M6 6.5a1 1 0 0 1 1-1h9a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1m0 14a1 1 0 0 1 1-1h9a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
