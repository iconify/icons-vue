<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2w4nqbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:louvred-roof-pergola" /></template>
<style>
.b2w4nqbdw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5h19M5 9.5V21M19 9.5V21M4.5 6.5l3-3.5m3 3.5l3-3.5m3 3.5l3-3.5");
}

</style>
