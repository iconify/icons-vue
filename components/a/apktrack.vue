<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rf1w9abyr"/><path class="ug9rg2_bw"/><path class="l0dps7k6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apktrack" /></template>
<style>
.l0dps7k6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 26.63a8.72 8.72 0 0 1 8.72 8.72v0a1.24 1.24 0 0 1-1.24 1.24h-15a1.24 1.24 0 0 1-1.24-1.24v0A8.72 8.72 0 0 1 24 26.63m-7.53-1.31l2.48 2.92m12.58-2.92l-2.48 2.92");
}

.rf1w9abyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.38 19.84h-7.86l-7.77-13a2 2 0 0 0-3.5 0l-7.77 13H6.62a3.12 3.12 0 0 0-3 3.93L8 40.08a2.84 2.84 0 0 0 2.74 2.1h26.5a2.84 2.84 0 0 0 2.76-2.1l4.41-16.31a3.12 3.12 0 0 0-3.03-3.93m-17.38-8l4.77 8h-9.54Zm-9.52 8h19.04");
}

.ug9rg2_bw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.45 34.16a1.23 1.23 0 1 1 1.22-1.22a1.23 1.23 0 0 1-1.22 1.22m7.12 0a1.23 1.23 0 1 1 1.22-1.22a1.23 1.23 0 0 1-1.22 1.22");
}

</style>
