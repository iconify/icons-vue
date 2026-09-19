<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="s-76gmbrm"/><circle class="xakrkvy8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:8-ball-pool" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s-76gmbrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.269 24a2.25 2.25 0 0 0-2.25 2.25h0a2.25 2.25 0 0 0 2.25 2.25h1.462a2.25 2.25 0 0 0 2.25-2.25h0a2.25 2.25 0 0 0-2.25-2.25m0 0a2.25 2.25 0 0 0 2.25-2.25h0a2.25 2.25 0 0 0-2.25-2.25H23.27a2.25 2.25 0 0 0-2.25 2.25h0A2.25 2.25 0 0 0 23.27 24m-.001 0h1.462");
}

.xakrkvy8r {
  cx: 24px;
  cy: 24px;
  r: 10px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
