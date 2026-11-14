<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqfy125qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blister-pack-grocery" /></template>
<style>
.aqfy125qk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 17.5l3.5-7h15.5l-3.5 7Zm4.25-7V7a2 2 0 0 1 4 0v3.5m3 0V7a2 2 0 0 1 4 0v3.5");
}

</style>
