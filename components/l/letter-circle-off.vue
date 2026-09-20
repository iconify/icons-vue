<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="kqnl2xbcs"/><path clip-rule="evenodd" class="nmutdfujr"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:letter-circle-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.kqnl2xbcs {
  fill-rule: evenodd;
  d: path("M20 6.5H6a1 1 0 0 0-1 1v11a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1v-11a1 1 0 0 0-1-1m-13 11v-9h12v9z");
}

.nmutdfujr {
  fill-rule: evenodd;
  d: path("m20.648 8.261l-7.045 6a1 1 0 0 1-1.301-.004l-6.955-6C4.645 7.652 5.073 6.5 6 6.5h14c.93 0 1.356 1.158.648 1.761M8.69 8.5l4.27 3.683L17.282 8.5z");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
