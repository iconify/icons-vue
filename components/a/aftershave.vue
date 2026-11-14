<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zordiabcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aftershave" /></template>
<style>
.zordiabcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5h5v3h-5Zm1 3V8C5.5 9 4 10.5 4 13v6.5q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028T6 21.5h6.917m2.934-9.77C15.404 9.97 13.953 8.818 11.5 8V5.5m6.5 8s3 3.5 3 5.25a3 3 0 0 1-6 0c0-1.75 3-5.25 3-5.25Z");
}

</style>
