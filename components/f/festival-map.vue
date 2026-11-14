<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c3eq30bzc"/><path class="j5khupbbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:festival-map" /></template>
<style>
.c3eq30bzc {
  d: path("m14.3 19.733l-.304.102q-.241.08-.495.077t-.492-.091l-4.496-1.635q-.249-.09-.513-.09t-.513.09l-2.974 1.082q-.085.031-.172.051q-.088.021-.178.031q-.089.009-.179.008q-.091-.001-.18-.012q-.089-.012-.177-.035q-.087-.022-.171-.055q-.084-.032-.163-.075q-.08-.042-.154-.094q-.073-.052-.14-.112t-.127-.128t-.11-.142t-.093-.154q-.041-.08-.073-.165q-.032-.084-.053-.171q-.022-.088-.032-.177q-.011-.09-.011-.18V6.051q0-.115.017-.228q.018-.114.052-.223q.035-.11.086-.213t.116-.197t.145-.177t.171-.152t.191-.126q.101-.055.209-.094l4-1.455q.249-.09.513-.09t.513.09l4.496 1.635q.238.087.492.091q.254.003.495-.077l3.53-1.177q.084-.028.171-.046t.176-.025t.177-.005t.176.016t.174.037q.085.024.168.058q.082.033.159.076q.078.043.15.095t.138.112q.065.06.123.128q.058.067.107.141q.05.074.09.153q.041.079.072.162t.051.17q.021.086.032.174t.01.177v5.592M8 3v15m5.5-13v8.7m0 4.7V20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j5khupbbi {
  d: path("m18.5 21.25l-2.5-4a2.75 2.75 0 1 1 5 0Z");
}

</style>
