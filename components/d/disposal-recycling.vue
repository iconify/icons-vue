<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wnw717b8a"/><path class="flgblmb8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:disposal-recycling" /></template>
<style>
.flgblmb8r {
  d: path("M19.621 15.379A3 3 0 0 1 17.5 20.5m-4.25-1.75l1.25-1.25l1.25 1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wnw717b8a {
  d: path("M3 3.5h16m-14 0l1.5 15q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01h2.597m5.067-8.635L17 3.5m-1.621 16.121A3 3 0 0 1 17.5 14.5m1.75 1.75l1.25 1.25l1.25-1.25");
}

</style>
