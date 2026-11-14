<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eroifcboy"/><path class="pis9-l1zm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:expansion-revenue" /></template>
<style>
.eroifcboy {
  d: path("M3 13a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pis9-l1zm {
  d: path("M7.5 7.5q.05-.242.121-.478q.072-.236.164-.465t.205-.449q.112-.219.244-.428t.281-.405t.317-.378t.349-.348t.379-.315q.197-.15.406-.281t.429-.242t.449-.204q.229-.091.465-.162t.479-.12q.241-.05.487-.077q.245-.027.492-.033q.246-.005.493.012q.246.016.49.055q.243.039.483.099q.239.061.472.142q.233.082.457.184q.225.102.439.224q.215.122.418.263q.203.14.392.298q.19.158.364.333q.175.174.333.364q.158.189.298.392q.141.203.263.418t.224.439t.184.457q.081.233.142.472q.06.24.099.483q.039.244.055.49q.021.299.008.599q-.012.299-.057.595q-.044.297-.121.586q-.076.29-.184.57t-.245.546t-.303.516q-.165.249-.357.48t-.407.438m-.821.654q-.87.566-1.886.776m-8-1a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m12 8v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
