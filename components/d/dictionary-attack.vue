<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikxkr0bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dictionary-attack" /></template>
<style>
.ikxkr0bml {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 19.5V5A2.5 2.5 0 0 1 7 2.5h12.5V17H7a2.5 2.5 0 0 0-2.5 2.5m0 0a2 2 0 0 0 2 2h13M9 9.75h.01m2.99 0h.01m2.99 0h.01");
}

</style>
