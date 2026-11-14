<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc75xkb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposition" /></template>
<style>
.kc75xkb6p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5zA2.5 2.5 0 0 1 12.5 5v4.5A2.5 2.5 0 0 1 10 12a2.5 2.5 0 0 1-2.5-2.5V5A2.5 2.5 0 0 1 10 2.5m-5.25 7q0 .129.006.258q.007.128.019.257q.013.128.032.255q.019.128.044.254q.025.127.056.252q.032.125.069.248t.081.245q.043.121.093.24q.049.119.104.236t.116.23t.127.224t.138.218q.071.107.148.21q.077.104.159.204q.081.099.168.195q.087.095.178.186t.186.178q.096.087.195.168q.1.082.204.159t.21.148q.107.072.218.138t.224.127t.23.116t.236.104q.119.05.24.093q.122.044.245.081t.248.069q.125.031.252.056q.126.025.254.044q.127.019.255.032q.129.012.257.019q.129.006.258.006q.643 0 1.268-.155q.624-.156 1.192-.457m2.314-2.453q.235-.514.355-1.067q.121-.552.121-1.118M10 14.75v5.75m-2.5 0h4.7m4.55-6.5H20a1.75 1.75 0 0 1 1.75 1.75v4.5A1.75 1.75 0 0 1 20 22h-3.25A1.75 1.75 0 0 1 15 20.25v-4.5A1.75 1.75 0 0 1 16.75 14m.75 2.75h1.75m-1.75 2.5h1.75");
}

</style>
