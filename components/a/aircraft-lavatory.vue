<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxghqv3zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aircraft-lavatory" /></template>
<style>
.gxghqv3zk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 2.5h1.5A1.75 1.75 0 0 1 8.5 4.25v5A1.75 1.75 0 0 1 6.75 11h-1.5A1.75 1.75 0 0 1 3.5 9.25v-5A1.75 1.75 0 0 1 5.25 2.5m10.508 12.354C14.82 15.926 13.376 16.5 11.5 16.5l.5 4H6L7 16c-2-1-3.5-2.5-3.5-5H17q-.001 1.159-.286 2.091M18.5 15.25v6.5m-3-2.25l3-2.25l3 2.25M17 21.75h3");
}

</style>
