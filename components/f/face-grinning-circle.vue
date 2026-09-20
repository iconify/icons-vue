<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ds5ly2jxw"/><path class="h5q-b7bfk"/><path clip-rule="evenodd" class="iit-9wrfq"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:face-grinning-circle" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ds5ly2jxw {
  fill-rule: evenodd;
  d: path("M13 20.5a7.5 7.5 0 1 0 0-15a7.5 7.5 0 0 0 0 15m0 2a9.5 9.5 0 1 0 0-19a9.5 9.5 0 0 0 0 19");
}

.h5q-b7bfk {
  d: path("M11.5 10.25a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0m5.5 0a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0");
}

.iit-9wrfq {
  fill-rule: evenodd;
  d: path("M8.409 14.538A.75.75 0 0 1 9 14.25h8a.75.75 0 0 1 .728.932L17 15l.728.182l-.001.003l-.001.004l-.003.013a4 4 0 0 1-.054.188a8.5 8.5 0 0 1-.908 2.008c-.68 1.087-1.878 2.352-3.761 2.352s-3.081-1.265-3.761-2.352a8.5 8.5 0 0 1-.962-2.196l-.003-.013v-.004l-.001-.002L9 15l-.728.182a.75.75 0 0 1 .137-.644m1.654 1.212c.117.265.265.56.448.852c.57.913 1.372 1.648 2.489 1.648s1.919-.735 2.489-1.648c.183-.292.33-.587.448-.852z");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

</style>
