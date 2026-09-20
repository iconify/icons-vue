<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v689vgqjr"/><path class="aavy257cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:listeningtrainer" /></template>
<style>
.aavy257cw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5v37h37");
}

.v689vgqjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 5.5C31.456 5.5 42.5 16.544 42.5 30.167M17.833 17.833c6.811 0 12.333 5.522 12.333 12.333");
}

</style>
