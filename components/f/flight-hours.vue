<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xssthjbmz"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flight-hours" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

.xssthjbmz {
  d: path("M15.465 12H5L2.5 4h2L7 7.5h11.5q.111 0 .221.011t.218.032q.108.022.214.054t.208.074q.102.043.2.095q.097.052.189.113t.177.132t.164.148q.078.078.148.164q.07.085.132.177q.061.092.113.189q.052.098.095.2q.042.102.074.208t.054.214t.032.218t.011.221q0 .108-.01.216t-.032.215q-.02.106-.051.21t-.072.205t-.091.197t-.11.187t-.127.175t-.143.163q-.076.077-.158.148q-.083.07-.172.132t-.184.115t-.194.096t-.202.078t-.209.058t-.213.037t-.216.017M8.5 12l-2 4.5H9l3-4.5m3.5 2.75h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

</style>
