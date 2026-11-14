<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awmvc_9cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aftershave" /></template>
<style>
.awmvc_9cj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.5h2A1.5 1.5 0 0 1 12.5 4A1.5 1.5 0 0 1 11 5.5H9A1.5 1.5 0 0 1 7.5 4A1.5 1.5 0 0 1 9 2.5m-.5 3V8C5.5 9 4 10.5 4 13v6.5q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028T6 21.5h6.917m2.934-9.77C15.404 9.97 13.953 8.818 11.5 8V5.5m6.5 8s3 3.5 3 5.25a3 3 0 0 1-6 0c0-1.75 3-5.25 3-5.25");
}

</style>
