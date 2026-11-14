<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0ienw9vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:glow-stars" /></template>
<style>
.x0ienw9vx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.029 9.334l.676 1.535a1.5 1.5 0 0 0 1.221.887l1.669.169a1.124 1.124 0 0 1 .636 1.957l-1.251 1.117a1.5 1.5 0 0 0-.466 1.436l.355 1.64a1.124 1.124 0 0 1-1.665 1.209l-1.449-.844a1.5 1.5 0 0 0-1.51 0l-1.449.844a1.124 1.124 0 0 1-1.665-1.209l.355-1.64a1.5 1.5 0 0 0-.466-1.436l-1.251-1.117a1.124 1.124 0 0 1 .636-1.957l1.669-.169a1.5 1.5 0 0 0 1.221-.887l.676-1.535a1.124 1.124 0 0 1 2.058 0M12 2.5v1.75M3.5 6.5l2 1.5m15-1.5l-2 1.5");
}

</style>
