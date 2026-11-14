<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6a89k52z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:liftoff-smoke" /></template>
<style>
.f6a89k52z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 17A3.5 3.5 0 0 1 8 11a4.5 4.5 0 0 1 8-.5a3.5 3.5 0 0 1 3.5 6.5m-17 0h19");
}

</style>
