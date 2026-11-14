<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmsc84fzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deal-handshake" /></template>
<style>
.vmsc84fzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5za1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 4 12a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 4 5m16 0za1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 20 12a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 20 5M5.5 6.5l4-2.5H14l4.5 2.5m0 5l-4.974 4.027m-.76.539c-.662.307-1.418.202-2.016-.316L5.5 11.5M14 4l-3.5 4.5m4.25 9.5l2 2L21 15.75");
}

</style>
