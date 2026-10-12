<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyaydrb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:donation-jar" /></template>
<style>
.hyaydrb3d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25v7.5m3-6.5h2.5l2.1-1.1a2 2 0 0 1 .95-.25h2.45a1.5 1.5 0 0 1 0 3H11.5m-5.75 4.35h6.6a3 3 0 0 0 1.85-.65l5.6-4.4a1.5 1.5 0 0 0-1.85-2.35l-3.2 2.5m-1.25-4.84c-.17 0-.34-.06-.46-.17c-1.39-1.15-3.22-2.62-3.22-4.59c0-1.14.87-2.06 1.96-2.06c.67 0 1.26.34 1.72.92c.46-.59 1.05-.92 1.72-.92c1.09 0 1.95.92 1.95 2.06c0 1.97-1.83 3.44-3.21 4.6c-.13.1-.29.17-.46.17Z");
}

</style>
