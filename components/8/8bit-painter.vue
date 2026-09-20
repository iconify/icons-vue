<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w422e2bfs"/><path class="yt-kdk--m"/><path class="fhw5m7b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:8bit-painter" /></template>
<style>
.fhw5m7b0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.834 32.222v1.028s0 1.027 1.027 1.027H29.14c1.028 0 1.028-1.027 1.028-1.027v-1.028m-8.224-4.11h4.111m-2.055 0v6.166m14.389-4.111H42.5m-4.111-4.111H42.5m-37 0h4.111M5.5 30.167h4.111");
}

.w422e2bfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.556 24v-1.028s0-1.028 1.027-1.028c1.028 0 1.028-1.027 1.028-1.027V18.86s0-1.028 1.028-1.028s1.028-1.027 1.028-1.027V14.75s0-1.028 1.028-1.028s1.027-1.028 1.027-1.028V10.64s0-1.028 1.028-1.028h2.056c1.027 0 1.027 1.028 1.027 1.028v2.055s0 1.028 1.028 1.028H29.14c1.028 0 1.028-1.028 1.028-1.028V10.64s0-1.028 1.028-1.028h2.055c1.028 0 1.028 1.028 1.028 1.028v2.055s0 1.028 1.028 1.028s1.028 1.028 1.028 1.028v2.056s0 1.027 1.027 1.027c1.028 0 1.028 1.028 1.028 1.028v2.056s0 1.027 1.028 1.027s1.028 1.028 1.028 1.028V24m0 8.222h-1.028c-1.028 0-1.028 1.028-1.028 1.028s0 1.028-1.028 1.028s-1.028 1.027-1.028 1.027s0 1.028-1.028 1.028H33.25c-1.028 0-1.028 1.028-1.028 1.028s0 1.028-1.028 1.028H16.805c-1.028 0-1.028-1.028-1.028-1.028s0-1.028-1.027-1.028h-2.056c-1.028 0-1.028-1.028-1.028-1.028s0-1.027-1.028-1.027s-1.027-1.028-1.027-1.028s0-1.028-1.028-1.028H7.555");
}

.yt-kdk--m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M17.834 21.944v4.111m12.333-4.111v4.111");
}

</style>
