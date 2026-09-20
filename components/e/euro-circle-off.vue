<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="gyhof6b7b"/><path clip-rule="evenodd" class="zf4jbtbrq"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:euro-circle-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gyhof6b7b {
  fill-rule: evenodd;
  d: path("M15.489 7C12.43 7 10 9.213 10 12.5c0 3.387 2.527 6 5.489 6c.743 0 1.451-.161 2.098-.454a1 1 0 1 1 .826 1.821a7.1 7.1 0 0 1-2.924.633C11.283 20.5 8 16.846 8 12.5C8 8.055 11.38 5 15.489 5q1.855.001 3.574 1.174a1 1 0 1 1-1.126 1.652C17.079 7.242 16.274 7 15.489 7");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.zf4jbtbrq {
  fill-rule: evenodd;
  d: path("M6 11a1 1 0 0 1 1-1h9a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1m0 3.5a1 1 0 0 1 1-1h8a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1");
}

</style>
