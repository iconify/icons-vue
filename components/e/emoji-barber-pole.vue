<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t8ajembps"/><path class="o255by20w"/><path class="a7ez3mb4t"/><path class="mw1_0ubpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-barber-pole" /></template>
<style>
.a7ez3mb4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.506 30.167l-15.704 9.25h-1.308V34.02L32.506 24z");
}

.mw1_0ubpb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.494 8.583h17.012v30.834H15.494z");
}

.o255by20w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.506 30.167l-15.704 9.25h5.235l10.47-6.167zm0-21.584H27.73l-12.235 6.938v6.166l17.012-10.02z");
}

.t8ajembps {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.893 8.583H15.107c-.854 0-1.546-.69-1.546-1.541h0c0-.852.692-1.542 1.546-1.542h17.786c.854 0 1.546.69 1.546 1.542h0c0 .851-.692 1.541-1.546 1.541m0 33.917H15.107c-.854 0-1.546-.69-1.546-1.542h0c0-.851.692-1.541 1.546-1.541h17.786c.854 0 1.546.69 1.546 1.541h0c0 .852-.692 1.542-1.546 1.542M27.73 8.583l-12.236 6.938v-3.084l6.543-3.854zM15.494 24.77l17.012-10.02v-3.083l-17.012 10.02zm17.012-3.853l-17.012 10.02v3.084L32.506 24z");
}

</style>
