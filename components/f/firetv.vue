<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="s_8dtobpm"/><path class="t716kvbrh"/><circle class="sz6wj6buq"/><path class="fqasbvd5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:firetv" /></template>
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

.fqasbvd5p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.76 20.2v5.3m15.54-6.95v5.95a1 1 0 0 0 1 1h.3m-2.35-5.3h2.1m-21.42 5.3v-6.6a1.4 1.4 0 0 1 1.4-1.4a1.63 1.63 0 0 1 1.42.59m-4 2.11h2.8m5.31 2a2 2 0 0 1 2-2m-2 0v5.3m7.23-1.01a2 2 0 0 1-1.74 1a2 2 0 0 1-2-2V22.2a2 2 0 0 1 2-2a2 2 0 0 1 2 2v.65h-4");
}

.s_8dtobpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.28 29.7c1.11-.45 3.09-1.05 3.69-.33s-.17 2.48-.92 3.8");
}

.sz6wj6buq {
  cx: 15.76px;
  cy: 17.75px;
  r: 0.7px;
  fill: currentColor;
}

.t716kvbrh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.8 30.22c1.76 1.4 7 3.54 12.49 3.54a17 17 0 0 0 10.16-3.08m3.8-10.48l-2 5.3l-2-5.3");
}

</style>
