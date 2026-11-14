<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvi5bri7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:force-feedback" /></template>
<style>
.mvi5bri7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6za2.5 2.5 0 0 1 2.5 2.5v7A2.5 2.5 0 0 1 12 18a2.5 2.5 0 0 1-2.5-2.5v-7A2.5 2.5 0 0 1 12 6m-9.5 6h4.25m-1.125-1.125l.064.064a1.5 1.5 0 0 1 0 2.122l-.064.064a.659.659 0 0 1-1.125-.466v-1.318a.659.659 0 0 1 1.125-.466M21.5 12h-4.25m1.125-1.125l-.064.064a1.5 1.5 0 0 0 0 2.122l.064.064a.659.659 0 0 0 1.125-.466v-1.318a.659.659 0 0 0-1.125-.466");
}

</style>
