<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-lqk-bdv"/><path class="b438kv4_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:headi" /></template>
<style>
.b438kv4_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.53 12.32l-5.17 8h5.17l-3.88 7.57");
}

.u-lqk-bdv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.49 18.35a15.34 15.34 0 0 0-30.61 1.49l-3.74 3.74a2.36 2.36 0 0 0 1.66 4h2.08v4.47a5.27 5.27 0 0 0 5.27 5.27h0v6.18h17.59V33.2a15.36 15.36 0 0 0 7.75-14.85");
}

</style>
