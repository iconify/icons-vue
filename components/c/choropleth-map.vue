<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-kwifrih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:choropleth-map" /></template>
<style>
.m-kwifrih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.99 3.81l5.77-.87q1.24-.19 1.09 1.05l-.7 5.77Q10 11 8.78 11.25l-4.81 1q-1.22.25-1.22-1v-6q0-1.25 1.24-1.44m10.46-.72l5.6 1.57q1.2.34 1.01 1.58l-.87 5.52Q20 13 18.76 12.84l-5.27-.68q-1.24-.16-1.11-1.4l.74-6.77q.13-1.24 1.33-.9M3.99 14.85l5.77-.7q1.24-.15 2.47.06l6.29 1.08q1.23.21.69 1.34l-1.67 3.49q-.54 1.13-1.79 1.06l-10.5-.61Q4 20.5 3.72 19.28l-.69-3.06q-.28-1.22.96-1.37");
}

</style>
