<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="on9f4vrxj"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:critical-ops" /></template>
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

.on9f4vrxj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.094 25.73v.044c0 1.923-1.29 3.482-2.88 3.482s-2.879-1.559-2.879-3.482v-3.548c0-1.923 1.29-3.482 2.88-3.482h0c1.59 0 2.879 1.559 2.879 3.482v.043M23.1 29.256c-1.59 0-2.88-1.559-2.88-3.482v-3.548c0-1.923 1.29-3.482 2.88-3.482s2.879 1.56 2.879 3.482v3.548c0 1.923-1.29 3.482-2.88 3.482m4.966 0V18.744h2.846c1.608 0 2.912 1.58 2.912 3.53s-1.304 3.53-2.913 3.53h-2.845m8.018 2.3c.533.839 1.202 1.152 2.132 1.152H39.5c1.198 0 2.169-1.174 2.169-2.623v-.011c0-1.448-.971-2.622-2.168-2.622h-1.42c-1.199 0-2.17-1.176-2.17-2.626h0c0-1.453.973-2.63 2.175-2.63h1.28c.93 0 1.598.312 2.13 1.151M13.788 24h4.346");
}

</style>
