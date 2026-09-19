<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="czmxqbc7j"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dns-changer-3" /></template>
<style>
.czmxqbc7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 18.688v10.624h2.39c2.524 0 4.649-2.125 4.649-4.648v-1.328c0-2.523-2.125-4.648-4.648-4.648zm9.98 10.624V18.688l7.04 10.624V18.688m3.074 9.429c.664.797 1.46 1.195 2.656 1.195h1.594c1.46 0 2.656-1.195 2.656-2.656S36.305 24 34.844 24h-1.727c-1.46 0-2.656-1.195-2.656-2.656s1.195-2.656 2.656-2.656h1.594c1.195 0 1.992.265 2.656 1.195");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
