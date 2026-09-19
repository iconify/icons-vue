<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="i5p7pm-xd"/><path class="q9_rxbc2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:droid-examiner" /></template>
<style>
.i5p7pm-xd {
  cx: 21.688px;
  cy: 21.688px;
  r: 16.188px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q9_rxbc2n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.134 33.134L42.5 42.5");
}

</style>
