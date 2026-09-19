<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xg4vr1a6s"/><circle class="mr0-ky2xl"/><circle class="oa_n5hegw"/><path class="svwu_wa3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fdroid-nethunter" /></template>
<style>
.mr0-ky2xl {
  cx: 17px;
  cy: 15.3px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oa_n5hegw {
  cx: 31px;
  cy: 15.3px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.svwu_wa3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.2 8.8h25.7a2.86 2.86 0 0 1 2.8 2.8V19a2.86 2.86 0 0 1-2.8 2.8H11.2A2.86 2.86 0 0 1 8.4 19v-7.4a2.734 2.734 0 0 1 2.8-2.8M5.5 5.9l3.7 3.7m2 15.2h25.7a2.86 2.86 0 0 1 2.8 2.8v11.7a2.86 2.86 0 0 1-2.8 2.8H11.2a2.86 2.86 0 0 1-2.8-2.8V27.6a2.734 2.734 0 0 1 2.8-2.8M42.5 5.9l-3.7 3.7");
}

.xg4vr1a6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.6 29.4v8m-13.2 0v-8l5.3 8v-8m2.6 0v8m0-4h5.3");
}

</style>
