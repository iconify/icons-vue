<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zgwajvbub"/><circle class="cpk0fnbgt"/><path class="dl_m47bto"/><path class="f6zjsghgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:device-care" /></template>
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

.dl_m47bto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.497 10.122a20 20 0 0 1 11.18 5.429M31.4 22.336a8.5 8.5 0 1 1-8.167 8.167m.16-3.818l-.16 3.818");
}

.f6zjsghgi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.457 30.674l4.936-3.989l4.935 4.057");
}

.zgwajvbub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.204 43.628A20 20 0 0 1 28.562 9.975");
}

</style>
