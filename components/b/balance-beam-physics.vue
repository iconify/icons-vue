<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j98d_cbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:balance-beam-physics" /></template>
<style>
.j98d_cbuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.5h19m-10.821 2.453l-.988 1.836A1.5 1.5 0 0 0 11.011 18h1.978a1.5 1.5 0 0 0 1.32-2.211l-.988-1.836a1.5 1.5 0 0 0-2.642 0M5.5 6.5H7A1.5 1.5 0 0 1 8.5 8v2A1.5 1.5 0 0 1 7 11.5H5.5A1.5 1.5 0 0 1 4 10V8a1.5 1.5 0 0 1 1.5-1.5m11.5 0h1.5A1.5 1.5 0 0 1 20 8v2a1.5 1.5 0 0 1-1.5 1.5H17a1.5 1.5 0 0 1-1.5-1.5V8A1.5 1.5 0 0 1 17 6.5");
}

</style>
