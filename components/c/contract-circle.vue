<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="a3xxuxmnr"/><path class="czql5vb5f"/><path class="uugwspwfq"/><path class="d60od6b4m"/><path class="qqz61wshz"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:contract-circle" /></template>
<style>
.a3xxuxmnr {
  d: path("M14.707 12.707a1 1 0 0 1-1.414-1.414l4-4a1 1 0 1 1 1.414 1.414z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.czql5vb5f {
  d: path("M14 13a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2z");
}

.d60od6b4m {
  d: path("M13 18a1 1 0 1 1-2 0v-4a1 1 0 1 1 2 0z");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.qqz61wshz {
  d: path("M8 15a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2z");
}

.uugwspwfq {
  d: path("M15 12a1 1 0 1 1-2 0V8a1 1 0 1 1 2 0zm-6.293 6.707a1 1 0 0 1-1.414-1.414l4-4a1 1 0 1 1 1.414 1.414z");
}

</style>
