<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="bvufnri4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:byu" /></template>
<style>
.bvufnri4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.124 18.5L23.481 24l-3.644-5.5m3.644 11V24m6.66-5.5v7.356a3.644 3.644 0 0 0 7.288 0V18.5M15.109 24a2.75 2.75 0 1 1 0 5.5H10.57v-11h4.538a2.75 2.75 0 1 1 0 5.5m.001 0h-4.538");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
