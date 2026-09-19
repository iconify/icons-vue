<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xlbhmccnr"/><path class="p6od72j-v"/><path class="m45j1bchy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:maf-carrefour" /></template>
<style>
.m45j1bchy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.346 39.356V23.157c0-5.358-5.24-11.31-12.67-8.673");
}

.p6od72j-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.654 39.356V23.157c0-6.9 4.898-14.657 12.022-14.657");
}

.xlbhmccnr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.2 8.5A14.45 14.45 0 0 0 6.72 22.98V39.5h13.868V24.394c0-1.561.52-2.942 1.329-3.823L24 23.06l2.083-2.489c.808.881 1.33 2.262 1.33 3.823V39.5h13.866V22.98c0-8.022-6.458-14.48-14.48-14.48z");
}

</style>
