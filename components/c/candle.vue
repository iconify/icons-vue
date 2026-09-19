<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="rsj8ambid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:candle" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.rsj8ambid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 15.021c-1.16 4.01-3.334 9.215-3.334 9.215c-.543 1.5-.23 3.487 2.018 3.487h2.632c2.078 0 2.518-2.104 1.976-3.604c0 0-2.513-5.871-3.292-9.098m0 11.171v5.489M18.66 42.5v-8.181c0-1.457.424-2.638.946-2.638h8.788c.523 0 .946 1.18.946 2.638V42.5");
}

</style>
