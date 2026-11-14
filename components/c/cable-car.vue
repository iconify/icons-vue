<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygr61zxru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cable-car" /></template>
<style>
.ygr61zxru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 6l19-2M4 5.75V21.5M20 4.25V21.5M11 10h2a3.5 3.5 0 0 1 3.5 3.5v2A3.5 3.5 0 0 1 13 19h-2a3.5 3.5 0 0 1-3.5-3.5v-2A3.5 3.5 0 0 1 11 10m1-5v5m-4.5 3.5h9");
}

</style>
