<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hu3y0onyy"/><path class="jtpnl8l7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:circle-search" /></template>
<style>
.hu3y0onyy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.457 40.51a17.6 17.6 0 0 1-6.293 1.154C10.408 41.664 2.5 33.755 2.5 24S10.408 6.336 20.164 6.336a17.63 17.63 0 0 1 13.753 6.579");
}

.jtpnl8l7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.666 24a8.503 8.503 0 0 1-17.006.001V24a8.503 8.503 0 0 1 8.503-8.503h0A8.503 8.503 0 0 1 28.666 24m-2.176 6.075l11.588 11.588M35.98 17.552v7.304m3.651-3.652h-7.303m10.107 0v6.13M45.5 24.27h-6.13m-.054 3.102v6.616m3.309-3.308h-6.617");
}

</style>
