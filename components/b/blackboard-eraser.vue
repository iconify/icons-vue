<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq3udlc0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blackboard-eraser" /></template>
<style>
.gq3udlc0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.991 8.567l7.282-2.651a2.625 2.625 0 0 1 3.365 1.569l.94 2.584a2.625 2.625 0 0 1-1.569 3.364l-7.282 2.651a2.625 2.625 0 0 1-3.365-1.569l-.94-2.584a2.625 2.625 0 0 1 1.569-3.364m-.757 5.596L16.45 9.717M15.5 19.5h.01M19 19h.01m.49-3.25h.01");
}

</style>
