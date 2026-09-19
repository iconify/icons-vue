<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="db1znh3dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jeep" /></template>
<style>
.db1znh3dl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.582 18.576V24.7a2.04 2.04 0 0 1-2.041 2.041h0A2.04 2.04 0 0 1 11.5 24.7v-.678m10.787 1.653a2.04 2.04 0 0 1-1.774 1.03h0a2.04 2.04 0 0 1-2.04-2.041v-1.327a2.04 2.04 0 0 1 2.04-2.041h0c1.127 0 2.041.914 2.041 2.041V24h-4.082m13.946-2.74v8.164m0-4.796a2.04 2.04 0 0 0 2.041 2.04h0a2.04 2.04 0 0 0 2.041-2.04V23.3a2.04 2.04 0 0 0-2.041-2.041h0a2.04 2.04 0 0 0-2.041 2.041m-3.158 2.41a2.04 2.04 0 0 1-1.774 1.03h0a2.04 2.04 0 0 1-2.04-2.04v-1.327a2.04 2.04 0 0 1 2.04-2.041h0a2.04 2.04 0 0 1 2.041 2.04v.664h-4.082");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
