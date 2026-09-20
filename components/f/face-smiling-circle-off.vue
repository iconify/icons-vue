<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ds5ly2jxw"/><path class="h5q-b7bfk"/><path clip-rule="evenodd" class="h1r1gl3hz"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:face-smiling-circle-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ds5ly2jxw {
  fill-rule: evenodd;
  d: path("M13 20.5a7.5 7.5 0 1 0 0-15a7.5 7.5 0 0 0 0 15m0 2a9.5 9.5 0 1 0 0-19a9.5 9.5 0 0 0 0 19");
}

.h1r1gl3hz {
  fill-rule: evenodd;
  d: path("M17.447 15.106a1 1 0 0 1 .447 1.341L17 16l.894.448v.001l-.002.003l-.003.005l-.006.013a2 2 0 0 1-.077.135q-.073.122-.21.308a4.8 4.8 0 0 1-.846.868C15.96 18.413 14.743 19 13 19s-2.96-.587-3.75-1.22a4.8 4.8 0 0 1-.847-.867a4 4 0 0 1-.286-.443l-.006-.013l-.003-.005l-.001-.003c-.001-.001-.001-.002.893-.449l-.894.447a1 1 0 1 1 1.798-.88q.025.046.1.146c.098.13.26.317.496.506c.46.368 1.243.781 2.5.781s2.04-.413 2.5-.78a2.8 2.8 0 0 0 .497-.507a2 2 0 0 0 .114-.172a1 1 0 0 1 1.336-.436");
}

.h5q-b7bfk {
  d: path("M11.5 10.25a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0m5.5 0a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
