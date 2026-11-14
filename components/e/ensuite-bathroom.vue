<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmp414bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ensuite-bathroom" /></template>
<style>
.pmp414bag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5.5v15M3 17h8.6M3 12.5h10.7m6.633.8q.159.172.284.37q.125.199.21.417q.086.218.129.448q.044.231.044.465v.173M7 9.5h2a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 9 12.5H7A1.5 1.5 0 0 1 5.5 11A1.5 1.5 0 0 1 7 9.5m7.25 8.5h7.5v1.5a2 2 0 0 1-2 2h-3.5a2 2 0 0 1-2-2Zm1.25 0v-2.5a1.25 1.25 0 0 1 2.5 0");
}

</style>
