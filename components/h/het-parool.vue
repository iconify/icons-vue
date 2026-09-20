<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q3q7v418h"/><path class="shz--mikb"/><path class="ify0scb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:het-parool" /></template>
<style>
.ify0scb4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.015 34.476a3.64 3.64 0 0 0 3.64 3.641m-3.64-3.641V5.5");
}

.q3q7v418h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.234 42.5h19.324m-5.543-16.799c4.225 0 7.65-4.522 7.65-10.1S26.24 5.5 22.016 5.5h7.65c5.58 0 10.101 4.522 10.101 10.1s-4.522 10.101-10.1 10.101z");
}

.shz--mikb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.558 38.117H8.234a3.64 3.64 0 0 0 3.641-3.641V9.14A3.64 3.64 0 0 0 8.234 5.5H28.61");
}

</style>
