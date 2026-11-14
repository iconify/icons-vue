<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf6nqdfgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:live-audio-room" /></template>
<style>
.vf6nqdfgx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3za2.5 2.5 0 0 1 2.5 2.5V10a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 9.5 10V5.5A2.5 2.5 0 0 1 12 3m-4.178 9.729a6.5 6.5 0 0 1 0-9.958m8.356 0a6.5 6.5 0 0 1 0 9.958M12 15.5V21m-3.5 0h7");
}

</style>
