<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0kja9b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:leaderboard-ai" /></template>
<style>
.x0kja9b6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25v-5q0-1 1-1H7.5q1 0 1-1v-2q0-1 1-1h5q1 0 1 1v4q0 1 1 1h3.75q1 0 1 1v3q0 1-1 1H3.75q-1 0-1-1M12 13.5V18m0-15.25q.33 2.42 2.75 2.75q-2.42.33-2.75 2.75q-.33-2.42-2.75-2.75q2.42-.33 2.75-2.75");
}

</style>
