<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f2vd3abks"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:efhub" /></template>
<style>
.f2vd3abks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.288 20.316v7.368m4.882-7.368v7.368m-4.882-3.698h4.882m2.033-3.67v4.928a2.441 2.441 0 0 0 4.882 0v-4.928M14.695 24h2.395m-2.395 3.684v-7.368h3.684m-5.936 6.439c-.317.555-.915.93-1.6.93h0A1.84 1.84 0 0 1 9 25.842v-1.197c0-1.018.825-1.842 1.842-1.842h0c1.018 0 1.842.824 1.842 1.842v.598H9M37.158 24a1.842 1.842 0 0 1 0 3.684h-3.04v-7.369h3.04a1.842 1.842 0 0 1 0 3.685m0 0h-3.04");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
