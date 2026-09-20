<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="m_7ikbc3l"/><path class="slbs5hhpe"/><path class="svgjwnbcw"/><path class="ybbiicqde"/><path class="cf3-vd85w"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:expand-circle-off" /></template>
<style>
.cf3-vd85w {
  d: path("M14 9a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2zM4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.m_7ikbc3l {
  d: path("M8.707 18.707a1 1 0 0 1-1.414-1.414l4-4a1 1 0 1 1 1.414 1.414z");
}

.slbs5hhpe {
  d: path("M8 19a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2z");
}

.svgjwnbcw {
  d: path("M9 18a1 1 0 1 1-2 0v-4a1 1 0 1 1 2 0zm5.707-5.293a1 1 0 0 1-1.414-1.414l4-4a1 1 0 1 1 1.414 1.414z");
}

.ybbiicqde {
  d: path("M19 12a1 1 0 1 1-2 0V8a1 1 0 1 1 2 0z");
}

</style>
