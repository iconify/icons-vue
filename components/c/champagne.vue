<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eke7dpmwq"/><rect class="z_f7otyqb"/><path class="df-fpnbgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:champagne" /></template>
<style>
.df-fpnbgj {
  d: path("m8.25 4.75l-1.75-1m9.25 1l1.75-1m-9 3.5l-1.75.5m8.75-.5l1.75.5");
}

.eke7dpmwq {
  d: path("M11.15 8.75h1.7q.9 0 .9.9v.7q0 .9.57 1.6l1.11 1.35q.57.7.57 1.6v5.45q0 .9-.9.9H8.9q-.9 0-.9-.9V14.9q0-.9.57-1.6l1.11-1.35q.57-.7.57-1.6v-.7q0-.9.9-.9M8 16.5h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_f7otyqb {
  width: 2.5px;
  height: 3px;
  x: 10.75px;
  y: 3px;
  rx: 0.6px;
}

</style>
