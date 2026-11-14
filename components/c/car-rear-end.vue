<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzc2d7zeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-rear-end" /></template>
<style>
.pzc2d7zeq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.25v-.668a1.75 1.75 0 0 1 .967-1.566l.511-.255a1.75 1.75 0 0 0 .783-.783l.755-1.511A1.75 1.75 0 0 1 7.082 8.5h.251a1.75 1.75 0 0 1 1.616 1.077l.75 1.802a2 2 0 0 1 .083.248l.166.664a1.8 1.8 0 0 1 .052.424v1.535A1.75 1.75 0 0 1 8.25 16h-4a1.75 1.75 0 0 1-1.75-1.75m12 0v-.849A1.68 1.68 0 0 1 15.25 12l.309-.206a1.75 1.75 0 0 0 .645-.783l.613-1.473A1.69 1.69 0 0 1 18.375 8.5h.043a1.75 1.75 0 0 1 1.566.967L21 11.5l.315.63a1.75 1.75 0 0 1 .185.783v1.337A1.75 1.75 0 0 1 19.75 16h-3.5a1.75 1.75 0 0 1-1.75-1.75M3.5 18a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M17 18a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-4.559-8.462za.516.516 0 0 0 .707.293a.203.203 0 0 1 .271.271a.516.516 0 0 0 .293.707a.203.203 0 0 1 0 .382a.516.516 0 0 0-.293.707a.203.203 0 0 1-.271.271a.516.516 0 0 0-.707.293a.203.203 0 0 1-.382 0a.516.516 0 0 0-.707-.293a.203.203 0 0 1-.271-.271a.516.516 0 0 0-.293-.707a.203.203 0 0 1 0-.382a.516.516 0 0 0 .293-.707a.203.203 0 0 1 .271-.271a.516.516 0 0 0 .707-.293a.203.203 0 0 1 .382 0");
}

</style>
