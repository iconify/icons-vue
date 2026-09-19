<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cmz8cms1k"/><path class="c3tbyjbyv"/><path class="smcmyqbik"/><path class="un8vgyb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:getflow" /></template>
<style>
.c3tbyjbyv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.27 19.192a10.479 10.479 0 1 1-4.453-4.458");
}

.cmz8cms1k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.864 15.954A21.452 21.452 0 1 1 32.488 4.321");
}

.smcmyqbik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.058 24.032a3.09 3.09 0 1 1-3.09-3.09m0 3.09L39.374 8.626m-6.669 6.594V9.17l6.67-6.67v6.126");
}

.un8vgyb3n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.78 15.295h6.05l6.67-6.67h-6.126");
}

</style>
