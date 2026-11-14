<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ftx05ud-t"/><path class="io5qj4_nh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:excess-amount" /></template>
<style>
.ftx05ud-t {
  d: path("M2.5 8.5a8.5 5 0 1 0 17 0a8.5 5 0 1 0-17 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.io5qj4_nh {
  d: path("M2.5 8.5v4q0 .123.01.245q.01.123.031.245t.051.244q.031.121.071.241q.041.121.092.24t.111.236t.131.233t.15.229t.169.225t.188.219t.205.214q.108.105.224.207q.115.102.24.2t.256.194q.133.095.273.186t.288.178q.147.086.302.169q.154.082.316.16q.161.078.329.151q.167.073.341.141q.173.069.352.132t.363.121t.373.11t.381.099t.389.089q.197.041.397.077q.199.035.402.065q.202.03.407.054t.411.042t.414.03t.416.018t.417.006q.62 0 1.233-.053m5.867-2.198q.341-.305.603-.635t.44-.679q.177-.349.267-.71t.09-.725v-4M15 18h6");
}

</style>
