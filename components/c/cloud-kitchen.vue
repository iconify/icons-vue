<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8ulzmbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cloud-kitchen" /></template>
<style>
.v8ulzmbqq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5h16M4 9.5v6q0 .172.017.343t.05.34q.034.168.084.333t.115.323t.147.311t.177.294q.095.143.204.276q.11.133.231.255q.122.121.255.231q.133.109.276.204q.142.096.294.177t.311.147q.158.065.323.115t.333.084q.169.033.34.05T7.5 19h3.342M17 13.315V9.5M8 2.75C6.75 4 9.25 5.25 8 6.5m4.5-3.75c-1.25 1.25 1.25 2.5 0 3.75m3.25 15H20a1.75 1.75 0 0 0 .25-3.5a3 3 0 0 0-5.75.5a1.5 1.5 0 0 0 1.25 3");
}

</style>
