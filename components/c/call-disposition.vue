<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tvbn_sb7r"/><path class="eh9rnoylm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:call-disposition" /></template>
<style>
.eh9rnoylm {
  d: path("M7 9.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8 5.75a.75.75 0 0 1 .75-.75H17L18 17l-1.25 1c.5 1.25 1 1.75 2.25 2.25L20 19l2 1v1.25a.75.75 0 0 1-.75.75c-3.5 0-6.25-2.75-6.25-6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tvbn_sb7r {
  d: path("M12.257 16.5H7L2.5 9.75L7 3h12q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132t.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194T21 5v9.5q0 .176-.031.349q-.03.173-.091.339q-.06.165-.149.317q-.088.152-.202.286");
}

</style>
