<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3dmgpurw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arthritis" /></template>
<style>
.l3dmgpurw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5V7c-2.5.25-3 3.5-.5 3.75h6c2.5-.25 2-3.5-.5-3.75V2.5m-5 19V17c-2.5-.25-3-3.5-.5-3.75h6c2.5.25 2 3.5-.5 3.75v4.5M3.75 9.5c-1 1.5 1 3 0 4.5m16.5-4.5c-1 1.5 1 3 0 4.5");
}

</style>
